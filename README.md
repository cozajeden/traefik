# Traefic

## Initial configuration (one time)

1. Create new volume
```bash
sudo mkdir /traefik
sudo mkdir /traefik/acme
sudo touch /traefik/acme/acme.json
sudo docker volume create traefik_acme --opt type=none --opt device=/traefik/acme/acme.json --opt o=bind
```