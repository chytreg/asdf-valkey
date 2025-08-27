# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test valkey https://github.com/dgertych-monterail/asdf-valkey.git "valkey-server --version"
```

Tests are automatically run in GitHub Actions on push and PR.
