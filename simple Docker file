# Use the official Python image from the Docker Hub
FROM python:3.11-slim

# Set a working directory
WORKDIR /app

# Copy the current directory contents into the container
COPY . .

# Install dependencies from requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Run the application
CMD ["python", "app.py"]
