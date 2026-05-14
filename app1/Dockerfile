FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy all files from current directory to /app in the container
COPY . .

# Install required Python packages
RUN pip install flask redis

# Inform Docker that the container listens on port 5000
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
