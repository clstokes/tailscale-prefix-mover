# tailscale-prefix-mover

[![status: experimental](https://img.shields.io/badge/status-experimental-blue)](https://tailscale.com/kb/1167/release-stages/#experimental)

## Usage

```shell
export TAILSCALE_TAILNET=...
export TAILSCALE_API_KEY=...

go run main.go --prefixes=100.72.0.0/13,100.96.0.0/11 --continue-on-error
Moving devices from [100.72.0.0/13 100.96.0.0/11] to [100.64.0.0/13 100.80.0.0/12]
Setting v4 address [100.67.178.27  ] to [nodeid:1234567890   / name:device123.example.ts.net]... done.
Setting v4 address [100.71.77.104  ] to [nodeid:9876543210   / name:device987.example.ts.net]... done.
Done.
```
# tailscale-prefix-mover