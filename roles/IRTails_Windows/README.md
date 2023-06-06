# IRTails_Windows

This role installs the necessary forensics tools for incident response on Windows machines.

## Requirements

- Windows operating system.
- Administrative privileges on the target machine.
- Internet access for downloading and installing the tools.

## Variables

The following variables can be customized in the `vars/main.yml` file:

- `windows_tool1`: Specify the first tool to be installed.
- `windows_tool2`: Specify the second tool to be installed.
- ...

## Usage

Include this role in your playbook by adding the followingfollowing to the `main.yml` file:

```yaml
- hosts: windows
  roles:
    - role: IRTails_Windows
