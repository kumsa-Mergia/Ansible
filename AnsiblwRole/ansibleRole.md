# Ansible Role: A Comprehensive Guide

**What is an Ansible Role?**

* An Ansible Role is a modular unit of automation that encapsulates a specific task or set of tasks. 
* It organizes files and directories in a well-defined structure, making it easy to reuse and share across different projects.
* Roles are fundamental to building complex and maintainable Ansible playbooks.

**Key Components of an Ansible Role:**

* **Tasks:** The core of a role, containing Ansible modules to perform specific actions (e.g., installing packages, configuring services, managing files).
* **Handlers:** Optional tasks that are triggered by changes detected by other tasks (e.g., restarting a service after configuration changes).
* **Variables:** Define default values or allow you to pass custom values to the role.
* **Templates:** Use Jinja2 templating to dynamically generate files based on variables.
* **Files:** Store static files that need to be copied to target systems (e.g., configuration files).
* **Defaults:** Set default values for variables that can be overridden by other variables.
* **Vars:** Define role-specific variables.
* **Meta:** Contains metadata about the role, such as dependencies and author information.

**Role Structure:**

roles/
├── role_name/
│   ├── tasks/
│   │   ├── main.yml
│   │   └── other_tasks.yml
│   ├── handlers/
│   │   └── main.yml
│   ├── templates/
│   │   ├── file1.j2
│   │   └── file2.j2
│   ├── files/
│   │   ├── file1
│   │   └── file2
│   ├── defaults/
│   │   └── main.yml
│   ├── vars/
│   │   └── main.yml
│   ├── meta/
│   │   └── main.yml
