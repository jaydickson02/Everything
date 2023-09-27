### Create the SSH Tunnel

```bash
ssh -D [LocalPort] -C -q -N [Username]@[ServerIPAddress]
```

### Configure the browser to use the SOCKS proxy

- Go to proxy settings
- Add `localhost` as the host and the port chosen in the SOCKS section
- Add DNS if applicable