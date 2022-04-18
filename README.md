quarkus-builder
===============

**This project is not an official Google Cloud project.**

## Usage

```yaml
# cloudbuild.yaml

steps:
- name: ghcr.io/shawnlabo/quarkus-builder
  args:
    - build
    - -Dquarkus.container-image.build=true
```

