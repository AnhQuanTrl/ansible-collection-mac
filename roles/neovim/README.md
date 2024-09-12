# Ansible Role: Neovim

Manage installation of Neovim using Bob (Neovim Version Manager).

## Requirements

Homebrew is installed.

## Role Variables

- `neovim_version`: The neovim version to be installed and used.
- `neovim_github_token`: The github token to be used to install neovim versions.

## Dependencies

`anhquantrl.mac.homebrew` (Soft dependency).

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

## License

MIT

## Author Information

[AnhQuanTrl](https://github.com/AnhQuanTrl)

