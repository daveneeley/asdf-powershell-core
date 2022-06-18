# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test powershell-core https://github.com/daveneeley/asdf-powershell-core.git "pwsh --version"
```

Tests are automatically run in GitHub Actions on push and PR.
