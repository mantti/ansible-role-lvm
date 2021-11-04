## ansible-role-lvm

Just easy way to create additional lvm-volumes.

just add host/group variable like:

```yaml
lvm_vgs:
 - { name: "lustre_vg", pvs: "/dev/sdb", pesize: "16"

lvm_volumes:
 - { name: "lustre_mgt", vg: "vg_root", size: "100%FREE"}
```
