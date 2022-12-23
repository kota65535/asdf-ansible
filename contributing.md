# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test ansible https://github.com/kota65535/asdf-ansible.git "ansible --version"
```

Tests are automatically run in GitHub Actions on push and PR.
