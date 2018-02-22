# Ansible Role: metricbeat

An Ansible Role that installs metricbeat on RedHat/CentOS or Debian/Ubuntu.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    metricbeat_version: "4.6"

The version of metricbeat to install (major and minor only).

## Dependencies

None.

## Example Playbook

    - hosts: metricbeat
      roles:
        - ffrizzo.metricbeat

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Fabiano Frizzo](https://www.ffrizzo.com/).
