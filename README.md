<div align="center">

# mise-slangroom-exec [![Build](https://github.com/matteo-cristino/mise-slangroom-exec/actions/workflows/build.yml/badge.svg)](https://github.com/matteo-cristino/mise-slangroom-exec/actions/workflows/build.yml) [![Lint](https://github.com/matteo-cristino/mise-slangroom-exec/actions/workflows/lint.yml/badge.svg)](https://github.com/matteo-cristino/mise-slangroom-exec/actions/workflows/lint.yml)

[slangroom-exec](https://github.com/dyne/slangroom-exec) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [mise-slangroom-exec  ](#mise-slangroom-exec--)
- [Contents](#contents)
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
mise plugin add slangroom-exec https://github.com/matteo-cristino/mise-slangroom-exec.git
```

slangroom-exec:

```shell
# Show all installable versions
mise list-all slangroom-exec

# Install specific version
mise install slangroom-exec@latest

# Set a version globally (on your ~/.tool-versions file)
mise global slangroom-exec@latest

# Now slangroom-exec commands are available
slangroom-exec --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/matteo-cristino/mise-slangroom-exec/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [matteo-cristino](https://github.com/matteo-cristino/)
