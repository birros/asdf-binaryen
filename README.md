<div align="center">

# asdf-binaryen [![Build](https://github.com/birros/asdf-binaryen/actions/workflows/build.yml/badge.svg)](https://github.com/birros/asdf-binaryen/actions/workflows/build.yml) [![Lint](https://github.com/birros/asdf-binaryen/actions/workflows/lint.yml/badge.svg)](https://github.com/birros/asdf-binaryen/actions/workflows/lint.yml)


[binaryen](https://github.com/WebAssembly/binaryen/wiki) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add binaryen
# or
asdf plugin add binaryen https://github.com/birros/asdf-binaryen.git
```

binaryen:

```shell
# Show all installable versions
asdf list-all binaryen

# Install specific version
asdf install binaryen latest

# Set a version globally (on your ~/.tool-versions file)
asdf global binaryen latest

# Now binaryen commands are available
wasm-opt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/birros/asdf-binaryen/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [birros](https://github.com/birros/)
