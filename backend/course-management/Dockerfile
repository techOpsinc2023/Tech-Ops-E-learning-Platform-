# Use an official Python runtime as a parent image
FROM python:3.10

# Set the working directory in the container
WORKDIR /app

# Copy requirements.txt to the container
COPY requirements.txt .

# Install application dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the Django application source code to the container
COPY . .

# Expose the port on which the application will run
EXPOSE 8000

# Define the command to start your Django application
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
