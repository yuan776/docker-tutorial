docker build -t my-python-app .
docker run -it -e AZURE_STORAGE_CONNECTION_STRING='placeholder' --rm --name my-running-app my-python-app