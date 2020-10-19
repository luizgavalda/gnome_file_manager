# Gnome File Manager

This role handles configure the default file manager for gnome-shell desktop.

## Requirements

The hosts you are targeting should have the following packages:

- gnome-shell

## Role Variables

| Variable            | Required | Default | Description                                                                                                                                                                                                                                                      |
| ------------------- | -------- | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| desktop_file_manager | &#9989;  | `[]`    | Name of file manager.<br><br>|

## Dependencies

None

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - role: luyz25.gnome_file_manager
      vars:
        desktop_file_manager: nemo
```

## License

MIT

## Author Information

Luiz Teixeira (@luyz25)
