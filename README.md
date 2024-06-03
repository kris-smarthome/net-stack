# net-stack
 
### Filesystem
This stack uses Docker bind mounts for configuration

- `~/docker/`
	- `adguard/`

### Environment variables
Environment variables are used for application configuration, the following variables must be set. An example .env file is included in this repository for reference.

| Environment variable | Value                             |
| -------------------- | --------------------------------- |
| CF_API               | Cloudflare API key                |
| CF_ZONE              | The domain A record to be updated |
| CDATA                | Container storage location        |