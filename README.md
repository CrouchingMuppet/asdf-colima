<div align="center">

# asdf-colima [![Build](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/build.yml/badge.svg)](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/build.yml) [![Lint](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/lint.yml/badge.svg)](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/lint.yml)

[Colima](https://github.com/abiosoft/colima) plugin for [mise-en-place](https://github.com/jdx/mise) and the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.
- `lima`: [Linux virtual machines](https://github.com/lima-vm/lima) on macOS.
- `docker-cli`:
  - [docker.com](https://www.docker.com) `brew install docker`
  - or [orbstack.dev](https://orbstack.dev) `brew install orbstack` on macOS

# Install

mise plugin:

Mise automatically installs plugins. If you want to use mise to install the `lima` dependency use:

```shell
mise global lima latest
```

asdf plugin:

```shell
# The pre-requisite `lima` can be optionally installed via asdf
asdf plugin add lima
asdf plugin add colima
```

Colima via mise:

```shell
# Show all installable versions
mise list-all colima

# Set a version globally (on your ~/.mise.toml file)
mise global colima latest

# Now colima commands are available
colima start
```

Check [mise-en-place](https://mise.jdx.dev/) documentation for more instructions on how to
install & manage versions.

Colima via asdf:

```shell
# Show all installable versions
asdf list-all colima

# Install specific version
asdf install colima latest

# Set a version globally (on your ~/.tool-versions file)
asdf global colima latest

# Now colima commands are available
colima start
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/CrouchingMuppet/asdf-colima/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Miles Parfitt](https://github.com/CrouchingMuppet/)
