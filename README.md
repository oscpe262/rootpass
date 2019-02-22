# Ansible role 'ansible-role-rootpass'

An Ansible role for setting up a random root password.

For now, it will save it to a local file, but it is intended to be extended to pushing it to a local keystorage.

## Requirements

## Role Variables
| Variable		| Default		| Comments (type) |
| :---			| :---			| :---		  |
| `root_shell` | `/bin/bash` | default shell for root user |
| `passpath` | /see defaults-file/ | This needs to be set and is the location where pass files are set. This is to be removed down the line. |

## Dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: ansible-role-rootpass
```

## Testing


## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
