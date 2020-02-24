# Ansible Role: Install CLI dev tools

Install and configure command-line development tools

Applying this role will set up a range of command-line development tools on the machine for use as a development environment.

### Linux

- man
- vim
- ctags # For vim
- Midnight Commander
- screen
- RBTools

### macOS

- m-cli
- clang-format
- Midnight Commander
- sqldiff
- sqlite
- ctags
- screen
- RBTools

### Windows

- Midnight Commander
- RBTools

## Requirements

None.

## Role Variables


## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc-cpp-cli-dev-tools

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas, based on existing roles at CCDC, by Jeff Geerling and google searches