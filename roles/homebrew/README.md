# Ansible Role: Homebrew

Manage installation of Homebrew and its packages, taps and cask apps.

## Requirements

XCode Command Line Tools must be installed in the managed node.

## Role Variables

- `homebrew_repo`: Homebrew Github repository.
- `homebrew_installed_packages`: Packages to be installed by Homebrew.
- `homebrew_uninstalled_packages`: Use this to uninstall packages.
- `homebrew_taps`: Homebrew taps to be tapped.
- `homebrew_cask_apps`: Install apps via `cask`.
- `homebrew_cask_uninstalled_apps`: Use this to uninstall `cask` apps.
- `homebrew_user`: Change this variable if we want to install Homebrew for another user (Multi-user setup).
- `homebrew_group`: The group that we would like to install Homebrew.
- `homebrew_clear_cache`: Should clear cache or not.

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

## License

MIT

## Author Information

[AnhQuanTrl](https://github.com/AnhQuanTrl)

