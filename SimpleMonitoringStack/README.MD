# Monitoring Play Ground
Here, a docker stack is provided for testing out commonly used monitoring toolsets.

## Setup
### Prerequisites
I recommend `Docker` for simplicity. `Podman` should work as well but was not tested and my need some adaptions, as podman compose does not work to well...

### Steps
1) Fill .env
2) Uncomment the services you want to try out in `docker-compose.yml`
3) `$ source .env`
4) `$ docker compose up -d`
5) Check `$ docker compose logs` and `./logs/grafana.log` for details

## Access the Services
- OpenSearch:
- InfluxDB:
- Grafana: 