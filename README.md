# IRTails-VMs
Automate your way into the IR world!!! 

This project contains an Incident Response Playbook that automates the installation of forensics tools on different operating systems. It uses Ansible to manage the deployment and configuration of the tools.

## Prerequisites

- Ansible installed on the control machine.
- Access to target machines with SSH connectivity (Linux) or WinRM (Windows).

## Usage

1. Clone this repository to your local machine.
2. Modify the `inventory.ini` file to include the target machines and assign them to the appropriate groups (`windows`, `linux`, `macos`).
3. Customize the variables in the roles to specify the desired tools to be installed.
4. Execute the playbook using the command: `ansible-playbook main.yml -i inventory.ini`.

## Directory Structure

The directory structure of this project is as follows:

- `roles/IRTails_Windows`: Role for installing forensics tools on Windows machines.
- `roles/IRTails_Linux`: Role for installing forensics tools on Linux machines.
- `roles/IRTails_OSX`: Role for installing forensics tools on macOS machines.
- `inventory.ini`: Inventory file specifying the target machines and their groups.
- `main.yml`: Main playbook file that includes the roles based on the target machine's group and operating system.

## ToDos

- include more tools

## License

This project is licensed under the [Apache License 2.0](LICENSE).
