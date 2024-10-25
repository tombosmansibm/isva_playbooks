# Notes

Toni created script with powershell to migrate the junctions to yaml

# junctions

- some are not idempotent - reason is the idempotency checks
  - server_port: integer
  
- need to have 1 master playbook to call other playbooks - use tags