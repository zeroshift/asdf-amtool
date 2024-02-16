<div align="center">

# asdf-amtool [![Build](https://github.com/zeroshift/asdf-amtool/actions/workflows/build.yml/badge.svg)](https://github.com/zeroshift/asdf-amtool/actions/workflows/build.yml) [![Lint](https://github.com/zeroshift/asdf-amtool/actions/workflows/lint.yml/badge.svg)](https://github.com/zeroshift/asdf-amtool/actions/workflows/lint.yml)

[amtool](https://prometheus.io/docs/alerting/latest/alertmanager/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-amtool  ](#asdf-amtool--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add amtool
# or
asdf plugin add amtool https://github.com/zeroshift/asdf-amtool.git
```

amtool:

```shell
# Show all installable versions
asdf list-all amtool

# Install specific version
asdf install amtool latest

# Set a version globally (on your ~/.tool-versions file)
asdf global amtool latest

# Now amtool commands are available
amtool --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zeroshift/asdf-amtool/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nick Prendergast](https://github.com/zeroshift/)
