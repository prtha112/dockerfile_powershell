docker build -t why . --build-arg FILENAME="./main.ps1"
docker run -e SQL_CONNECTION_STRING="your_connection_string" why
