# Cloudflare DDNS Script

Cloudflare API v4 Dynamic DNS Update in Bash, and `jq` required to decode json string.

```
$ jq -h
jq - commandline JSON processor [version 1.5]
```

## Usage

```shell
bash <(curl -fsSL git.io/cf-ddns.sh) \
    -k cloudflare-api-key \
    -u user@example.com \
    -z example.com \
    -h host.example.com \
    -t A|AAAA
    -f true
```
