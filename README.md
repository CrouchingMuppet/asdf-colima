<div align="center">

# asdf-colima [![Build](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/build.yml/badge.svg)](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/build.yml) [![Lint](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/lint.yml/badge.svg)](https://github.com/CrouchingMuppet/asdf-colima/actions/workflows/lint.yml)


[colima](https://github.com/abiosoft/colima) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add colima
# or
asdf plugin add colima https://github.com/CrouchingMuppet/asdf-colima.git
```

colima:

```shell
# Show all installable versions
asdf list-all colima

# Install specific version
asdf install colima latest

# Set a version globally (on your ~/.tool-versions file)
asdf global colima latest

# Now colima commands are available
colima version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/CrouchingMuppet/asdf-colima/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Miles Parfitt](https://github.com/CrouchingMuppet/)
