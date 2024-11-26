# Use the official Python image as the base
FROM python:3.12-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory's contents to /app inside the container
COPY . /app

# Install dependencies
RUN pip install flask

# Expose port 8080 for the Flask app
EXPOSE 8080

# Command to run the Flask app
CMD ["python", "app.py"]
