# Ansible role to install bat
Installs [bat](https://github.com/sharkdp/bat) (a cat replacement) via [Ansible](https://ansible.com).

---

- [Ansible Galaxy: aeimer.install_bat](https://galaxy.ansible.com/aeimer/install_bat)
- [Github: aeimer/ansible-install-bat](https://github.com/aeimer/ansible-install-bat)

<!--
## Variables
| Name | Default Value | Description |
| ---- | ------------- | ----------- |
|  |  |  |
-->

## Example Playbook
```bash
- host: localhost
  roles:
    - aeimer.install_bat
```

## Known Issues
- This is only tested with Ubuntu
