# Create_Fedora_workstation_box

```
packer build --only=virtualbox-iso fedora.json

vagrant box add localhost/fedora33-workstation box/virtualbox/fedora33-workstation-0.1.0.box
```
# Reference

[Box cutter fedora](https://github.com/boxcutter/fedora)