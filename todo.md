# Todo - Ansible bootstrapping

- [ ] Make a wrapper for ansible pull clients.
- [ ] using this command `sudo ansible-pull --url https://github.com/fullstopslash/ansible-bootstrap init.yml local.yml -i hosts.yml`
- [ ] Make a user list
- [ ] add tor service to all distros
  - [ ] get the /etc/tor/torrc onto the system
- [ ] use "become" "$USER" for appropriate packagers:
  - [ ] pipx
  - [ ] cargo
  - [ ] flatpak
- [ ] add all common firewall rules for my network
- [ ] automate atuin login:
  - [ ] atuin login --username $() --password $() --key $()
