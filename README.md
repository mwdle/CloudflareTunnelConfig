# Cloudflare Tunnel Configuration

This repository runs Cloudflare Tunnel as a rootless Podman Quadlet. It shares
`cloudflare-tunnel.network` with Caddy and forwards remotely managed tunnel
routes to Caddy through the existing `https://Caddy` origin.

## Podman secret

Create the tunnel token as the rootless Quadlet user:

```console
podman secret create cloudflare_tunnel_token -
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
