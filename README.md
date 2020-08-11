[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/0)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/0)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/1)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/1)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/2)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/2)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/3)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/3)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/4)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/4)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/5)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/5)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/6)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/6)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/images/7)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-desktop-softwares/links/7)

Ansible Role: fabiodbr.desktop-softwares
=========

This role installs softwares.

Requirements
------------

None.

Role Variables
--------------

user
anaconda_url
anaconda_md5
rstudio_version

Dependencies
------------

None.

Example Playbook
----------------
```yaml
---
- hosts: localhost
  connection: local
  roles:
    - role: ansible-role-desktop-softwares
      become: yes
      vars:
        install:
          - anaconda
          - apt-packages
          - bash-powerline-shell
          - google-chrome
          - docker-ce
          - gimp
          - gnome-themes-github
          - gnome-theme-flat-remix
          - google-cloud-sdk
          - graphics-drivers
          - keybase
          - menlo-font
          - meslolgs-font # vscode terminal font
          - nerdfonts
          - paper-icon-theme
          - python3-packages
          - R-base
          - R-studio
          - terminator
          - typora
          - virtualbox
          - visual-studio-code
          - vscode-extensions
```

License
-------

MIT

Author Information
------------------

This role was created in 2020 by [Fabio Rizzi](https://github.com/fabiodbr).
