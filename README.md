<div align="center">

# asdf-arm-none-eabi [![Build](https://github.com/meatherly/asdf-arm-none-eabi/actions/workflows/build.yml/badge.svg)](https://github.com/meatherly/asdf-arm-none-eabi/actions/workflows/build.yml) [![Lint](https://github.com/meatherly/asdf-arm-none-eabi/actions/workflows/lint.yml/badge.svg)](https://github.com/meatherly/asdf-arm-none-eabi/actions/workflows/lint.yml)

[arm-none-eabi](https://github.com/meatherly/arm-none-eabi) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add arm-none-eabi
# or
asdf plugin add arm-none-eabi https://github.com/meatherly/asdf-arm-none-eabi.git
```

arm-none-eabi:

```shell
# Show all installable versions
asdf list-all arm-none-eabi

# Install specific version
asdf install arm-none-eabi latest

# Set a version globally (on your ~/.tool-versions file)
asdf global arm-none-eabi latest

# Now arm-none-eabi commands are available
arm-none-eabi --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/meatherly/asdf-arm-none-eabi/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Michael Eatherly](https://github.com/meatherly/)
