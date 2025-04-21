<div align="center">

# asdf-nvim-config [![Build](https://github.com/TiagoTi/asdf-nvim-config/actions/workflows/build.yml/badge.svg)](https://github.com/TiagoTi/asdf-nvim-config/actions/workflows/build.yml) [![Lint](https://github.com/TiagoTi/asdf-nvim-config/actions/workflows/lint.yml/badge.svg)](https://github.com/TiagoTi/asdf-nvim-config/actions/workflows/lint.yml)

[nvim-config](https://github.com/TiagoTi/nvim-config) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add nvim-config
# or
asdf plugin add nvim-config https://github.com/TiagoTi/asdf-nvim-config.git
```

nvim-config:

```shell
# Show all installable versions
asdf list-all nvim-config

# Install specific version
asdf install nvim-config latest

# Set a version globally (on your ~/.tool-versions file)
asdf global nvim-config latest

# Now nvim-config commands are available
nvim-config --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/TiagoTi/asdf-nvim-config/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [tiago.cipriano](https://github.com/TiagoTi/)
