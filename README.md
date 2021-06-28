# Ansible Role: Install CLI dev tools

Install and configure command-line development tools useful when building the CSD Portfolio

Applying this role will set up a range of command-line development tools on the machine for use as a development environment.

### Linux

- man
- vim
- ctags
- Midnight Commander
- screen
- diffutils

### macOS

- m-cli
- clang-format
- Midnight Commander
- sqldiff
- sqlite
- ctags
- screen
- diffutils
### Windows

- Midnight Commander
- diffutils

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc.cpp_cli_dev_tools

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas, based on existing roles at CCDC, by Jeff Geerling and google searches