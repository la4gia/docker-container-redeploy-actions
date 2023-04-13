# Action to Re-Deploy All Running Containers

Currently only works with self-hosted runner


## Example workflow

```yaml
name: Re-Deploy Containers

on:
  workflow_dispatch:

jobs:
  re-deploy:
    runs-on: self-hosted
    steps:
      - uses: la4gia/docker-container-redeploy-actions@v0.0.0-alpha
```
