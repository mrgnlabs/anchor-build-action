# Anchor Build Action
Github action for running anchor builds

### Example
```yaml
build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Anchor Build 
        uses: mrgnlabs/anchor-build-action@v0.3
        with:
            args: <custom build args>
```
