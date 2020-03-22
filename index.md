
## Default Variables

### bartender_license

License key for Bartender

#### Default value

```yaml
bartender_license:
```

### bartender_license_holders_name

Name of the license holder

#### Default value

```yaml
bartender_license_holders_name:
```

### bartender_started

Start in background after install

#### Default value

```yaml
bartender_started: true
```

### bartender_user

User to run user-specific commands

#### Default value

```yaml
bartender_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
