# Visual Studio Code

Adds the Visual Studio Code yum repository and installs Visual Studio Code.

## Requirements

None

## Role Variables

| Variable            | Required | Default | Description                                                                                                              |
| ------------------- | -------- | ------- | ------------------------------------------------------------------------------------------------------------------------ |
| `vscode_extensions` | :x:      | `[]`    | A list of Visual Studio Code extensions to install. Packages can be found [here](https://marketplace.visualstudio.com/). |

## Dependencies

None

## Example Playbook

```yaml
- hosts: localhost
  vars:
    vscode_extensions:
      - ms-python.python
  roles:
      - jaredhocutt.vscode
```
