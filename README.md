# amprnet

Get AMPRnet gateways IPs with API and generates ip routes.

Needs `curl` and `jq`.

## Usage & options
```
$ ./parse_json -h
usage: ./parse_json [-u|--user <username>] [-k|--key <api key>] [-U|--url <api url>] [-c|-l|-b]
```

| Short option | Long option | Description |
| ----------- | ----------- | ----------- |
| -u | --user | Mandatory if not defined in source |
| -k | --key | Mandatory if not defined in source |
| -U | --url | Only if not default value defined in source |
| -b | --bsd | default mode |
| -c | --cisco | Cisco ip routes |
| -l | --linux | Linux iproute2 |
