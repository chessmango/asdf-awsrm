<div align="center">

# asdf-awsrm [![Build](https://github.com/chessmango/asdf-awsrm/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-awsrm/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-awsrm/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-awsrm/actions/workflows/lint.yml)


[awsrm](https://github.com/jckuester/awsrm) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add awsrm https://github.com/chessmango/asdf-awsrm.git
```

awsrm:

```shell
# Show all installable versions
asdf list-all awsrm

# Install specific version
asdf install awsrm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global awsrm latest

# Now awsrm commands are available
awsrm --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-awsrm/graphs/contributors)!

# License

See [LICENSE](LICENSE)
