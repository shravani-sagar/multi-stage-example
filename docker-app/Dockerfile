# Use a base Python image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy files
COPY . .

# Install dependencies (optional if app.py uses Flask, etc.)
RUN pip install flask

# Set the command to run the app
CMD ["python", "app.py"]
