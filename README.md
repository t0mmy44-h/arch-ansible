# Arch Linux Ansible

Sets up a new desktop or laptop with my Arch Linux environment.

see [vimwiki](../../notes/vimwiki/linuxenv/arch-bootstrap.md) for a list of packages

## TODO
- [ ] enable and start sshd
- [ ] clone down dotfiles (ordering?)
- [ ] install userspace things
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
