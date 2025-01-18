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

