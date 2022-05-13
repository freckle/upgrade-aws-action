**This project has been archived**. This was useful back when GitHub
runners came with CLI v1 installed, but they now have v2 already. That
makes this action unneccessary (and harmful, since it errors when v2 is
already present).

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
