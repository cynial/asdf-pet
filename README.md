<div align="center">

# asdf-pet [![Build](https://github.com/cynial/asdf-pet/actions/workflows/build.yml/badge.svg)](https://github.com/cynial/asdf-pet/actions/workflows/build.yml) [![Lint](https://github.com/cynial/asdf-pet/actions/workflows/lint.yml/badge.svg)](https://github.com/cynial/asdf-pet/actions/workflows/lint.yml)

[pet](https://github.com/knqyf263/pet) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

```shell
asdf plugin add pet
# or
asdf plugin add pet https://github.com/cynial/asdf-pet.git
```

```shell
# Show all installable versions
asdf list-all pet

# Install specific version
asdf install pet latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pet latest

# Now pet commands are available
pet --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/cynial/asdf-pet/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [cynial](https://github.com/cynial/)
