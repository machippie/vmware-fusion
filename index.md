
## Default Variables

### vmware_fusion_machines

#### Default value

```yaml
vmware_fusion_machines: []
```

### vmware_fusion_user

User to run user-specific commands

#### Default value

```yaml
vmware_fusion_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
