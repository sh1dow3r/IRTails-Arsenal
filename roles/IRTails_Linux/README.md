
# IRTails_Linux

```markdown
# IRTails_Linux

This role installs the necessary forensics tools for incident response on Linux machines.

## Requirements

- Linux operating system.
- Root or sudo access on the target machine.
- Internet access for downloading and installing the tools.

## Variables

The following variables can be customized in the `vars/main.yml` file:

- `linux_tool1`: Specify the first tool to be installed.
- `linux_tool2`: Specify the second tool to be installed.
- ...

## Usage

Include this role in your playbook by adding the following to the `main.yml` file:

```yaml
- hosts: linux
  roles:
    - role: IRTails_Linux
