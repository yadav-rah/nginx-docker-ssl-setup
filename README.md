# Setting up SSL certificates for Nginx in Docker Environment

## Wildcard SSL CertBot Setup

```bash
  certbot certonly \
    --manual \
    --preferred-challenges=dns \
    --email sample_email@domain.com
    --server https://acme-v02.api.letsencrypt.org/directory \
    - *.sample_domain.com
    --agree-tos \
    --force-renewal" certbot
```
