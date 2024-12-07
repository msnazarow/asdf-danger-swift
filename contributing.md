# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test danger-swift https://github.com/danger/asdf-danger-swift.git "danger-swift --version"
```

Tests are automatically run in GitHub Actions on push and PR.
