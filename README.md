<div align="center">

# asdf-hashlink [![Build](https://github.com/0b1kn00b/asdf-hashlink/actions/workflows/build.yml/badge.svg)](https://github.com/0b1kn00b/asdf-hashlink/actions/workflows/build.yml) [![Lint](https://github.com/0b1kn00b/asdf-hashlink/actions/workflows/lint.yml/badge.svg)](https://github.com/0b1kn00b/asdf-hashlink/actions/workflows/lint.yml)


[hashlink](https://github.com/ohmrun/asdf-hashlink) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add hashlink
# or
asdf plugin add hashlink https://github.com/0b1kn00b/asdf-hashlink.git
```

hashlink:

```shell
# Show all installable versions
asdf list-all hashlink

# Install specific version
asdf install hashlink latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hashlink latest

# Now hashlink commands are available
hashlik --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/0b1kn00b/asdf-hashlink/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [0b1kn00b](https://github.com/0b1kn00b/)
