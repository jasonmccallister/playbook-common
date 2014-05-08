Ansible Playbook for Common Packages
=========================
This will install common packages for Ubuntu/Debian via `apt`.

### Sample Usage

##### Use with Tower

- Add this playbook to a **projects** directory available to Tower or through **SCM**.
- Create a **Job Template** using this playbook and provide necessary options.
- Create two variables to pass to this playbook.
	- my_hosts: **groupname**
- Run the job and see magic happen!

### Task List

- [ ] Add check for yum or apt package manager

### Feedback

Please contribute any feedback or problems through this repositories issues or  [@themccallister](https://twitter.com/themccallister).
