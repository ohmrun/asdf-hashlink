# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test hashlink https://github.com/0b1kn00b/asdf-hashlink.git "hashlik --version"
```

Tests are automatically run in GitHub Actions on push and PR.
