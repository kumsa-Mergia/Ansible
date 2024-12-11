# Ansible

![Ansible Logo](ansible.png)

# Ansible Repository

Welcome to my Ansible Repository! This repository contains a collection of Ansible playbooks and roles organized into directories based on specific use cases and functionalities.

## Directory Structure

Here is the structure of the repository with a brief description of each directory:

- **ConditionalExecution**
  - Contains playbooks that demonstrate the use of conditional statements in Ansible tasks to control task execution based on specific conditions.

- **ExecutinCommand**
  - Includes playbooks that execute shell commands or scripts on remote nodes using Ansible modules like `command` or `shell`.

- **GatheringFact-and-Debugging**
  - Focuses on gathering facts about remote nodes using the `setup` module and debugging playbooks with the `debug` module.

- **NotifyHandlerls**
  - Features examples of how to use handlers in Ansible to perform tasks triggered by notifications from other tasks.

- **Package**
  - Contains playbooks to manage packages on remote systems, such as installing, updating, or removing software.

- **Files**
  - Includes playbooks that handle file operations like copying, managing permissions, or creating symbolic links.

- **StorageManagment**
  - Playbooks dedicated to managing storage resources such as partitions, logical volumes, and file systems on remote systems.

- **Usermanagment**
  - Covers user and group management tasks, including creating, modifying, or removing users and groups.

## Getting Started

### Prerequisites

- Ansible installed on your control node.
- SSH access to your target nodes.
- Appropriate inventory configuration.

### Usage

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/kumsa-Mergia/Ansible.git
   ```
2. Navigate to the directory of the desired functionality:
   ```bash
   cd your-ansible-repo/<directory-name>
   ```
3. Run the playbook:
   ```bash
   ansible-playbook <playbook-name>.yml
   ```

## Contributing

Contributions are welcome! If you have ideas to improve the playbooks or add new functionalities, feel free to fork the repository, make your changes, and submit a pull request.


## Author

Created by [Kumsa Mergia](mailto:kumsamega@gmail.com).

