# Ansible Role : deploy_sysstat

[![CI](https://github.com/glillico/ansible-role-deploy_sysstat/workflows/CI/badge.svg)](https://github.com/glillico/ansible-role-deploy_sysstat/actions?query=workflow%3ACI)

Installs and configures sysstat.

## Requirements

None.

## Role Variables

### defaults/main.yml

|Variable|Description|
|---|---|
|dsys_service_name|The name of the systemd service.|
|dsys_package_name|The name of the sysstat package to install.|
|dsys_service_enable|Enable and start the sysstat service when set to `true`.|

## Dependencies

None.
## Example Playbook

    - hosts: servers
      roles:
        - glillico.deploy_sysstat

## License

MIT

## Author Information

Created in 2024 by Graham Lillico.
