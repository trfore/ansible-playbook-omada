# ansible-playbook-omada

A complete example playbook for [ansible-role-omada-install].

## Quick Instructions

- Clone this repo: `git clone https://github.com/trfore/ansible-playbook-omada.git`
- Change into the cloned repo directory: `cd ansible-playbook-omada`
- Install the requirements: `ansible-galaxy install -r requirements.yml`
- Update the `inventory` file for your environment (example below)
  ```
  [all]
  omada-controller ansible_host=192.168.1.10 ansible_user=ubuntu
  ```
- Run the playbook: `ansible-playbook main.yml`

### Note on `ansible.cfg`

- This is an optional file with sensible values for most local/homelab environments and includes optimizations for SSH connections. Yet, all values are commented out to avoid potential conflicts.

## License

MIT

## Author Information

Taylor Fore (https://github.com/trfore)

## References

- https://github.com/trfore/ansible-role-omada-install
- https://galaxy.ansible.com/trfore/omada_install

[ansible-role-omada-install]: https://github.com/trfore/ansible-role-omada-install
