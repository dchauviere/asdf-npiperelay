<div align="center">

# asdf-npiperelay [![Build](https://github.com/dchauviere/asdf-npiperelay/actions/workflows/build.yml/badge.svg)](https://github.com/dchauviere/asdf-npiperelay/actions/workflows/build.yml) [![Lint](https://github.com/dchauviere/asdf-npiperelay/actions/workflows/lint.yml/badge.svg)](https://github.com/dchauviere/asdf-npiperelay/actions/workflows/lint.yml)

[npiperelay](https://github.com/albertony/npiperelay) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add npiperelay
# or
asdf plugin add npiperelay https://github.com/dchauviere/asdf-npiperelay.git
```

npiperelay:

```shell
# Show all installable versions
asdf list-all npiperelay

# Install specific version
asdf install npiperelay latest

# Set a version globally (on your ~/.tool-versions file)
asdf global npiperelay latest

# Now npiperelay commands are available
npiperelay.exe --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dchauviere/asdf-npiperelay/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Chauviere](https://github.com/dchauviere/)
