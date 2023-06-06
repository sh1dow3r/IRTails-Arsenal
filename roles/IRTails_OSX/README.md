
# IRTails_OSX

```markdown
# IRTails_OSX

This role installs the necessary forensics tools for incident response on macOS machines.

## Requirements

- macOS operating system.
- Administrator privileges on the target machine.
- Internet access for downloading and installing the tools.

## Variables

The following variables can be customized in the `vars/main.yml` file:

- `macos_tool1`: Specify the first tool to be installed.
- `macos_tool2`: Specify the second tool to be installed.
- ...

## Usage

Include this role in your playbook by adding the following to the `main.yml` file

```yaml
- hosts: macos
  roles:
    - role: IRTails_OSX
