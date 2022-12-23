<div align="center">

# asdf-ansible [![Build](https://github.com/kota65535/asdf-ansible/actions/workflows/build.yml/badge.svg)](https://github.com/kota65535/asdf-ansible/actions/workflows/build.yml) [![Lint](https://github.com/kota65535/asdf-ansible/actions/workflows/lint.yml/badge.svg)](https://github.com/kota65535/asdf-ansible/actions/workflows/lint.yml)


[ansible](https://github.com/ansible/ansible) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add ansible
# or
asdf plugin add ansible https://github.com/kota65535/asdf-ansible.git
```

ansible:

```shell
# Show all installable versions
asdf list-all ansible

# Install specific version
asdf install ansible latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ansible latest

# Now ansible commands are available
ansible --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kota65535/asdf-ansible/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tomohiko Ozawa](https://github.com/kota65535/)
