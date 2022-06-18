<div align="center">

# asdf-powershell-core [![Build](https://github.com/daveneeley/asdf-powershell-core/actions/workflows/build.yml/badge.svg)](https://github.com/daveneeley/asdf-powershell-core/actions/workflows/build.yml) [![Lint](https://github.com/daveneeley/asdf-powershell-core/actions/workflows/lint.yml/badge.svg)](https://github.com/daveneeley/asdf-powershell-core/actions/workflows/lint.yml)


[powershell-core](https://github.com/daveneeley/asdf-powershell-core) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add powershell-core
# or
asdf plugin add powershell-core https://github.com/daveneeley/asdf-powershell-core.git
```

powershell-core:

```shell
# Show all installable versions
asdf list-all powershell-core

# Install specific version
asdf install powershell-core latest

# Set a version globally (on your ~/.tool-versions file)
asdf global powershell-core latest

# Now powershell-core commands are available
pwsh --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/daveneeley/asdf-powershell-core/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dave Neeley](https://github.com/daveneeley/)
