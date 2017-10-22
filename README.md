# ansible-role-gitconfig

Ansible role to configure git.

## Role Variables

```
gitconfig_packages:
 - git
 - gitg

gitconfig_user: someuser

gitconfig_set: true
gitconfig:
  <section>:
    <key>: <value>

gitconfig_set_ignore: true
gitconfig_ignore:
  - ".vagrant"
  - ".DS_Store"

gitconfig_set_commit_message: true
```

See defaults directory for full listing.

## Inspiration

[kosssi/ansible-role-gitconfig](https://github.com/kosssi/ansible-role-gitconfig)

[thomaslorentsen/ansible-git-client](https://github.com/thomaslorentsen/ansible-git-client)
