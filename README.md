# Projectile: Keymaker

This is a tool for generating self-signed certificates for the Projector or things like that.

## Positional parameters:

1. Authority name
2. Server name
3. Should we create CA? "true" or "false"
2. "IP" or "DNS"
3. IP or DNS record itself (the value)
4. Password

## Example:

```
./projectile-keymaker projector idea true IP 192.168.1.1 mypassword
```
