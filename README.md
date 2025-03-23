# React Login Demo

A simple React login application with Docker support. This application features a login form that accepts:
- Username: DongNguyen
- Password: 123

Upon successful login, the user is redirected to a welcome page.

## Running with Docker

### Prerequisites
- Docker and Docker Compose installed on your system

### Steps to run the application

1. Clone or download this repository

2. Open a terminal and navigate to the project directory

3. Build and start the Docker container:
   ```
   docker-compose up
   ```

4. The application will be available at:
   ```
   http://localhost:3000
   ```

5. To stop the application, press `Ctrl+C` in the terminal or run:
   ```
   docker-compose down
   ```

## Login Credentials

- Username: `DongNguyen`
- Password: `123`

After entering the correct credentials, you will be redirected to the welcome page.

## Troubleshooting

- If you encounter any issues with port 3000 being already in use, you can change the port mapping in `docker-compose.yml`
- Make sure no other applications are running on port 3000 on your host machine 