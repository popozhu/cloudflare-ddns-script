# Cloudflare DDNS Script

Cloudflare API v4 Dynamic DNS Update in Bash, without unnecessary requests

## Usage

```shell
bash <(curl -fsSL git.io/cf-ddns.sh) \
    -k cloudflare-api-key \
    -u user@example.com \
    -z example.com \
    -h host.example.com \
    -f true
```
