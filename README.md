# Upgrade AWS Action

GitHub Action to upgrade AWS to the latest version

## Usage

```yaml
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: freckle/upgrade-aws-action@main
      - run: aws --version
```

---

[LICENSE](./LICENSE)
