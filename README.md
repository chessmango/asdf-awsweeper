<div align="center">

# asdf-awsweeper [![Build](https://github.com/chessmango/asdf-awsweeper/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-awsweeper/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-awsweeper/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-awsweeper/actions/workflows/lint.yml)


[awsweeper](https://github.com/jckuester/awsweeper) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add awsweeper https://github.com/chessmango/asdf-awsweeper.git
```

awsweeper:

```shell
# Show all installable versions
asdf list-all awsweeper

# Install specific version
asdf install awsweeper latest

# Set a version globally (on your ~/.tool-versions file)
asdf global awsweeper latest

# Now awsweeper commands are available
awsweeper --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-awsweeper/graphs/contributors)!

# License

See [LICENSE](LICENSE)
