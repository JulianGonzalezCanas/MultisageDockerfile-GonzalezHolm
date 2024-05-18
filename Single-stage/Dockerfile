# Stage 1: Build stage
FROM python:3.10

WORKDIR /app

# Copy requirements.txt to the container
COPY requirements.txt .
RUN pip install --upgrade pip
RUN pip install --upgrade setuptools wheel

# Install dependencies
RUN pip install --no-cache-dir --upgrade -r requirements.txt

# Copy the application source code
COPY . .
RUN rm requirements.txt

# Expose port 5000
EXPOSE 5000

CMD ["python","app.py", "--host=0.0.0.0"]
