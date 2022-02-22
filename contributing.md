# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test awsweeper https://github.com/chessmango/asdf-awsweeper.git "awsweeper --version"
```

Tests are automatically run in GitHub Actions on push and PR.
