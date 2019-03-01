## ansible-role-lvm

Just easy way to create additional lvm-volumes.

just add host/group variable like:

```yaml
lvm_volumes:
 - { name: "lustre_mgt", vg: "vg_root", size: "100%FREE"}
```
