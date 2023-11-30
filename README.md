<div align="center">

# asdf-solc [![Build](https://github.com/leovct/asdf-solc/actions/workflows/build.yml/badge.svg)](https://github.com/leovct/asdf-solc/actions/workflows/build.yml) [![Lint](https://github.com/leovct/asdf-solc/actions/workflows/lint.yml/badge.svg)](https://github.com/leovct/asdf-solc/actions/workflows/lint.yml)

[solc](https://github.com/leovct/asdf-solc) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add solc
# or
asdf plugin add solc https://github.com/leovct/asdf-solc.git
```

solc:

```shell
# Show all installable versions
asdf list-all solc

# Install specific version
asdf install solc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global solc latest

# Now solc commands are available
solc --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/leovct/asdf-solc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Léo Vincent](https://github.com/leovct/)
