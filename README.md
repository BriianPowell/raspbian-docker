# Raspbian Docker Compose

### Main uses:

* Configure HASS
* Configure Postgres
* Configure MQTT Broker

### Steps

1. Install Docker

```bash
sudo apt install do   ker
```

2. Install Docker Compose

```bash
curl -s https://packagecloud.io/install/repositories/Hypriot/Schatzkiste/script.deb.sh | sudo bash
sudo apt install docker-compose
```

3. Start the container

```bash
docker-compose up -d
```

### Usefule Scripts

```bash
scp hass-postgres.env user@ip:/home/GitHub/raspbian-docker
```