<div align="center">

# asdf-doggo [![Build](https://github.com/iamd3vil/asdf-doggo/actions/workflows/build.yml/badge.svg)](https://github.com/iamd3vil/asdf-doggo/actions/workflows/build.yml) [![Lint](https://github.com/iamd3vil/asdf-doggo/actions/workflows/lint.yml/badge.svg)](https://github.com/iamd3vil/asdf-doggo/actions/workflows/lint.yml)

[doggo](https://github.com/mr-karan/doggo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add doggo
# or
asdf plugin add doggo https://github.com/iamd3vil/asdf-doggo.git
```

doggo:

```shell
# Show all installable versions
asdf list-all doggo

# Install specific version
asdf install doggo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global doggo latest

# Now doggo commands are available
doggo --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/iamd3vil/asdf-doggo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sarat Chandra](https://github.com/iamd3vil/)
