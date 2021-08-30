# Arch Linux Ansible

Sets up a new desktop or laptop with my Arch Linux environment.

see [vimwiki](../../notes/vimwiki/linuxenv/arch-bootstrap.md) for a list of packages

## TODO
- [X] install userspace things
  - [ ] break down into files
- [ ] clone down dotfiles (ordering?)
  - [ ] checkout after clone
  - [ ] figure out what's missing from installs (fonts etc.)
- [ ] install laptop things
- [ ] prerequisites
  - [ ] ansible.sh
  - [ ] wifi shit
  - [ ] git, ansible, pip3, hashivault

Yay install example:
```yaml
- name: install packages from AUR with yay
  aur:
    use: yay
    name:
      - package_name_1
      - package_name_2
```
