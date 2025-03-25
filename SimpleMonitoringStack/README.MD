# Monitoring Play Ground
Here, a `Docker` stack is provided for testing out commonly used monitoring toolsets.
Docker can be installed with a [convenience script](https://docs.docker.com/engine/install/fedora/#install-using-the-convenience-script):
- `$ curl -fsSL https://get.docker.com -o get-docker.sh`
- `$ sudo sh get-docker.sh `

## Setup
### Prerequisites
I recommend `Docker` for simplicity. `Podman` should work as well but was not tested and my need some adaptions, as podman compose does not work to well...

### Steps
1) Fill `.env`
2) Comment out the unnecessary services in `docker-compose.yml`
3) `$ source .env`
4) `$ docker compose up -d`
5) Check `$ docker compose logs` and `./logs/grafana.log` for details

## Access the Services
- OpenSearch:
- InfluxDB:
- Grafana: 