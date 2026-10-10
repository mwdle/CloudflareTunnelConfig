# Cloudflare Tunnel Configuration

A rootless Podman Quadlet configuration for `cloudflared`

## Podman secret

Create the tunnel token as the rootless Quadlet user:

```console
podman secret create cloudflare_tunnel_token -
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details
