# Use official Python 3.13.1 image as base
FROM python:3.13.1-slim

# Set the working directory in the container
WORKDIR /app

# Install the required dependencies directly
RUN pip install --no-cache-dir Flask==2.2.2 mysql-connector-python==8.0.28 werkzeug==2.2.2

# Copy the application code into the container
COPY . /app/

# Expose the Flask app port
EXPOSE 5000

# Set the default command to run the Flask app
CMD ["python", "index.py"]

