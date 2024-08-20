# Obtain certs

```
docker-compose run \
  --rm template.certbot certonly \
  --webroot \
  --webroot-path=/var/www/certbot \
  --email pieceowater@gmail.com \
  --agree-tos \
  --no-eff-email \
  -d api.template.lotof.services
```
