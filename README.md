# action-dockerfile-tools

A GitHub Action that downloads and installs
[dockerfile-tools](https://github.com/escapace/dockerfile-tools), enabling the generation of a JSON
Abstract Syntax Tree (AST) and the listing of build stages from dockerfiles. It provides a way to
automate Dockerfile analysis and validation within CI/CD pipelines.

```yaml
- uses: escapace/action-dockerfile-tools@v0.1.0
  with:
    version: latest
    cache: true
```
