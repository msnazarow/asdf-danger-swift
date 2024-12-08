<div align="center">

# asdf-danger-swift [![Build](https://github.com/msnazarow/asdf-danger-swift/actions/workflows/build.yml/badge.svg)](https://github.com/msnazarow/asdf-danger-swift/actions/workflows/build.yml) [![Lint](https://github.com/msnazarow/asdf-danger-swift/actions/workflows/lint.yml/badge.svg)](https://github.com/msnazarow/asdf-danger-swift/actions/workflows/lint.yml)

[danger-swift](https://danger.systems/swift/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add danger-swift
# or
asdf plugin add danger-swift https://github.com/msnazarow/asdf-danger-swift.git
```

danger-swift:

```shell
# Show all installable versions
asdf list-all danger-swift

# Install specific version
asdf install danger-swift latest

# Set a version globally (on your ~/.tool-versions file)
asdf global danger-swift latest

# Now danger-swift commands are available
danger-swift --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/msnazarow/asdf-danger-swift/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Михаил Назаров](https://github.com/danger/)
