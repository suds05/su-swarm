# Use an official Python runtime as a parent image
FROM python:3.10-slim

# Set the working directory in the container
WORKDIR /swarm

# Copy the current directory contents into the container at /swarm
COPY . /swarm

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt