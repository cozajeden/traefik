# Traefic

## Initial configuration (one time)

> Create new volume

```bash
sudo mkdir /traefik
sudo mkdir /traefik/acme_volume
sudo touch /traefik/acme_volume/acme.json
sudo chmod 600 /traefik/acme_volume/acme.json
sudo chown -R root:root /traefik/acme_volume/acme.json
```

## Create/Update stack

```bash
./update_prod.sh
```

## Atach services to traefik

> Use `test.yml` as the template for labeling your services
