# Use an official Ubuntu base image
FROM ubuntu:latest

# Install necessary packages
RUN apt-get update && apt-get install -y \
    curl \
    git \
    vim

# Set the working directory
WORKDIR /app

# Copy the application files
COPY . .

# Command to run the application
CMD ["bash"]