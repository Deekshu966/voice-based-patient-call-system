# voice-based-patient-call-system

# Steps to Run the Code

## 1. Build the Docker Container
To build the Docker container, use the following command:
```bash
sudo docker-compose build --no-cache
```
If `sudo` is not required on your system, you can omit it:
```bash
docker-compose build --no-cache
```

## 2. Start the Docker Container
To start the Docker container, run:
```bash
sudo docker-compose up -d
```
Again, if `sudo` is not needed, use:
```bash
docker-compose up -d
```

## 3. View Logs
To view the logs of the running container, execute:
```bash
sudo docker-compose logs -f
```
Or without `sudo`:
```bash
docker-compose logs -f
```

## 4. Access the API
Once the container is running, you can access the API at the following URL:
```
http://0.0.0.0:8000
```
To use the API documentation, append `/docs` to the URL:
```
http://0.0.0.0:8000/docs
```

