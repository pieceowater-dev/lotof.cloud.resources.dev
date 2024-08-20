# Obtain certs

```
docker-compose run \
  --rm certbot certonly \
  --webroot \
  --webroot-path=/var/www/certbot \
  --email pieceowater@gmail.com \
  --agree-tos \
  --no-eff-email \
  -d api.template.lotof.services \
  -d template.lotof.services \
  -d -d *.lotof.services
```
