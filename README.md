# Ansible Playbook: rpi_get_cpu_gpu_temp
![GitHub last commit](https://img.shields.io/github/last-commit/lpwoodhouse/playbook_rpi_get_cpu_gpu_temp)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/lpwoodhouse/playbook_rpi_get_cpu_gpu_temp)
![GitHub top language](https://img.shields.io/github/languages/top/lpwoodhouse/playbook_rpi_get_cpu_gpu_temp)

## Part of my Raspberry Pi cluster project

## Purpose

Gathers information of current CPU/GPU temperatures on rpi hosts.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see ```defaults/main.yml```)
```shell
inc_fan_settings: true
```
## Dependencies

None

## Example Playbook
```yaml
    - hosts: all
      roles:
        - rpi_temps
```

## License

[![GitHub](https://img.shields.io/github/license/lpwoodhouse/playbook_rpi_get_cpu_gpu_temp)](LICENSE)

## Author Information

This role was created in 2022 by [Lee Woodhouse](https://www.leewoodhouse.com/)
