1. Create a Git repository for the project and include the ML model code and API server code.
2. Implement the API server using a Python web framework like Flask or FastAPI.
3. Set up a GitHub Actions workflow to automate model testing and deployment on each push to the repository.
4. Build a Docker container for the API server with the necessary dependencies and the pre-trained model.
5. Use Docker Hub to store the Docker image.
6. Deploy the Docker container on AWS EC2. Access the application using public IP address of the Instance and add the port of web app:http://ec2-18-118-5-166.us-east-2.compute.amazonaws.com:8080/docs
7. Set up an API Gateway to expose the API endpoint securely:https://r0hso6j8d4.execute-api.us-east-2.amazonaws.com
