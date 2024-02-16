# Adblocking

Start with `docker-compose up -d` and configure a proxy host to port `3000`.


## Troubleshooting

If port 53 is already in use, deactivate `systemd-resolved`:

```
sudo systemctl stop systemd-resolved
sudo systemctl disable systemd-resolved
sudo systemctl mask systemd-resolved
```
