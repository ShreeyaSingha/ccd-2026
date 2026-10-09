# 1. Use ultra-lightweight official Python base
FROM python:3.11-alpine
# 2. Set container working directory
WORKDIR /app
# 3. Copy our server code into the container
COPY server.py .
# 4. Document that our service listens on port 8080
EXPOSE 8080
# 5. Command executed when container starts
CMD ["python", "server.py"]