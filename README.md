# action-dockerfile-tools

GitHub Action for installing
[dockerfile-tools](https://github.com/escapace/dockerfile-tools), a command-line utility for
parsing Dockerfiles into JSON syntax trees, listing named build stages, and extracting cache mounts
with `ARG` value expansion.

```yaml
- uses: escapace/action-dockerfile-tools@v0.2.2
  with:
    version: latest
    cache: true
```
