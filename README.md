# PHP React Status Dashboard

A simple dashboard that displays PHP and database status information using React and TypeScript.

## Prerequisites

- Node.js (v14 or higher)
- PHP (v8.2 or higher)
- Apache/Nginx web server
- MySQL/MariaDB database

## Project Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. **Install Frontend Dependencies**
   ```bash
   cd frontend
   npm install
   ```

3. **Configure Backend**
   - Ensure PHP is installed and configured on your system
   - Configure your database connection in the backend configuration file
   - Set up Apache/Nginx to serve the PHP files

4. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   DB_HOST=localhost
   DB_USER=your_username
   DB_PASSWORD=your_password
   DB_NAME=your_database
   ```

5. **Start Development Server**
   ```bash
   npm start
   ```
   The application will be available at `http://localhost:3000`
