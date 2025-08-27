<div align="center">

# asdf-valkey [![Build](https://github.com/chytreg/asdf-valkey/actions/workflows/build.yml/badge.svg)](https://github.com/chytreg/asdf-valkey/actions/workflows/build.yml) [![Lint](https://github.com/chytreg/asdf-valkey/actions/workflows/lint.yml/badge.svg)](https://github.com/chytreg/asdf-valkey/actions/workflows/lint.yml)

[valkey](https://github.com/chytreg/valkey) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `make`, `gcc` (or `clang`), and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html)

For detailed dependency information, build options, and platform support, see the [Valkey README](https://github.com/valkey-io/valkey/blob/unstable/README.md) and [dependencies documentation](https://github.com/valkey-io/valkey/blob/unstable/deps/README.md).

# Install

Plugin:

```shell
asdf plugin add valkey
# or
asdf plugin add valkey https://github.com/chytreg/asdf-valkey.git
```

valkey:

```shell
# Show all installable versions
asdf list-all valkey

# Install specific version
asdf install valkey latest

# Set a version globally (on your ~/.tool-versions file)
asdf global valkey latest

# Now valkey commands are available
valkey-server --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chytreg/asdf-valkey/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dariusz Gertych](https://github.com/chytreg/)
