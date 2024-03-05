# gitea-runner-docker-permission-fix

```yaml
name: Dummy Name
on:
  push:
jobs:
  dummy:
    runs-on: ubuntu-latest
    steps:
    - uses: https://github.com/imlonghao/gitea-runner-docker-permission-fix@main
    - run: |
      docker ps
```
