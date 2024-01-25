## Running the Dockerfile

To run the Dockerfile, follow these steps:

1. Build the Docker image:
    ```bash
    docker build -t myapp .
    ```

2. Run the Docker container:
    ```bash
    docker run -d -p 8080:80 myapp
    ```

3. Access the application in your browser:
    ```
    http://localhost:8080
    ```

Make sure you have Docker installed and running on your machine before executing these commands.
