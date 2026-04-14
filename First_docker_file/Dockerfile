FROM ubuntu:latest

# Set the working directory in the image
WORKDIR /app

# Copy the files from host file system to the image file system
COPY . /app

# Install the necessary package
RUN apt-get update && apt-get install -y python3 python3-pip

# Set the environment variable
ENV NAME world

# Run a command to start a application
CMD ["python3" , "app.py"]
