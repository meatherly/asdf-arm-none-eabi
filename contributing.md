# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test arm-none-eabi https://github.com/meatherly/asdf-arm-none-eabi.git "arm-none-eabi --help"
```

Tests are automatically run in GitHub Actions on push and PR.
