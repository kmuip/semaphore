# Ansible maintenance playbooks

- playbooks/verify-access.yml: verify SSH, Python and sudo access.
- playbooks/update-ubuntu.yml: update Ubuntu packages; use --check to preview.

Provide the managed inventory group, connection settings, SSH host keys and credentials outside this repository.
Reboots require reboot_if_required=true; package removals are refused.
Container images and operating-system release upgrades are outside the playbook scope.