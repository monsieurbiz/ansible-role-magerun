# Ansible Magerun Role

It just installs Magerun and Magerun2 (for Magento 2).

## Requirements

* Ansible version 2.*

# Role Variables

You can override all the variables in `defaults/main.yml` in tour own vars.

## Example Playbook

    - hosts: servers
      roles:
         - { role: monsieurbiz.magerun }

## License

MIT

## Authors

* Jacques Bodin-Hullin - [@jacquesbh](https://twitter.com/jacquesbh)
