
## Default Variables

### bartender_automatically_update

Automatically update

#### Default value

```yaml
bartender_automatically_update: true
```

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

### bartender_reduce_update_frequency_on_battery

Reduce update frequency

#### Default value

```yaml
bartender_reduce_update_frequency_on_battery: true
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

### bartender_welcome_message_again

Update welcome message

#### Default value

```yaml
bartender_welcome_message_again: true
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
