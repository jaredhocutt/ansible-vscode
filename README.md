# Visual Studio Code

This role handles configuring the Visual Studio Code repository and then
install Visual Studio Code.

In a previous version of this role, it would also install extensions as well,
but this was removed due extensions such as settings-sync, which is integrated
directly with Visual Studio Code and provides a more robust feature set.

## Requirements

The hosts you are targeting should have the following packages:

- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

None

## Example Playbook


```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.vscode
```

## License
-------

MIT

## Author Information
------------------

Jared Hocutt (@jaredhocutt)
