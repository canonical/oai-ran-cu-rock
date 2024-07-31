# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:oai-ran-cu_2.1.1_amd64.rock docker-daemon:oai-ran-cu:2.1.1
docker run -d oai-ran-cu:2.1.1
```
