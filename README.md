
# asdf-sup3

[sup3](https://github.com/lsr0/sup3) plugin for the [asdf version manager](https://asdf-vm.com).

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`.

## Install

Plugin:

```shell
asdf plugin add sup3 https://github.com/erkiesken/asdf-sup3.git
```

sup3:

```shell
# Show all installable versions
asdf list-all sup3

# Install specific version
asdf install sup3 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sup3 latest

# Now sup3 commands are available
sup3 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

## License

See [LICENSE](LICENSE) © [Erki Esken](https://github.com/erkiesken/)
