

# Express TypeScript App

This project is a Express application written in TypeScript. It serves an HTML file and is set up to run in Docker.

## Prerequisites

- Node.js and npm
- Docker (for running in Docker)

## Running Without Docker

1. **Clone the Repository:**

   ```sh
   git clone [https://github.com/ryankontos/boulder-nevada.git](https://github.com/ryankontos/boulder-nevada.git)
   cd boulder-nevada
   ```

2. **Install Dependencies:**

   ```sh
   npm install
   ```

3. **Build the TypeScript Code:**

   ```sh
   npm run build
   ```

4. **Start the Application:**

   ```sh
   npm run serve
   ```

5. **Access the Application:**

   - Open your browser and go to `http://localhost:3000`.

## Running With Docker

### Docker Installation on Windows

1. **Download Docker Desktop:**
   - Go to the [Docker Desktop for Windows download page](https://www.docker.com/products/docker-desktop) and download the installer.

2. **Install Docker Desktop:**
   - Open the downloaded installer and follow the instructions.

3. **Run Docker Desktop:**
   - Open Docker Desktop from the Start menu.

4. **Verify the Installation:**
   - Open Command Prompt or PowerShell and run:
     ```sh
     docker --version
     ```

### Running the Project in Docker

1. **Build the Docker Image:**

   ```sh
   docker build -t boulder-nevada .
   ```

2. **Run the Docker Container:**

   ```sh
   docker run -p 3000:3000 boulder-nevada
   ```

3. **Access the Application:**

   - Open your browser and go to `http://localhost:3000`.
