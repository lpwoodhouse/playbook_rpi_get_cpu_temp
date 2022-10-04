# Ansible Playbook: rpi_get_cpu_gpu_temp

### Part of my Raspberry Pi cluster project

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

MIT

## Author Information

This role was created in 2022 by [Lee Woodhouse](https://www.leewoodhouse.com/)
