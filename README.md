<div align="center">

# asdf-clojure-lsp [![Build](https://github.com/armed/asdf-clojure-lsp/actions/workflows/build.yml/badge.svg)](https://github.com/armed/asdf-clojure-lsp/actions/workflows/build.yml) [![Lint](https://github.com/armed/asdf-clojure-lsp/actions/workflows/lint.yml/badge.svg)](https://github.com/armed/asdf-clojure-lsp/actions/workflows/lint.yml)

[clojure-lsp](https://clojure-lsp.io/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add clojure-lsp
# or
asdf plugin add clojure-lsp https://github.com/armed/asdf-clojure-lsp.git
```

clojure-lsp:

```shell
# Show all installable versions
asdf list-all clojure-lsp

# Install specific version
asdf install clojure-lsp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clojure-lsp latest

# Now clojure-lsp commands are available
clojure-lsp --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/armed/asdf-clojure-lsp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Artem Medeu](https://github.com/armed/)
