# install 

```sh
wget https://archive.org/download/en_windows_7_ultimate_with_sp1_x64_dvd_u_677332_202006/en_windows_7_ultimate_with_sp1_x64_dvd_u_677332.iso
```

# create

```sh
mkdir name
```

# go to the folder

```sh
cd "name"
```
# create disk
```sh
qemu-img create -f qcow2 disk.img 20G
```

# start

```sh
qemu-system-x86_64 -boot d -cdrom win7.iso -m 2048 -hda disk.img
```

© termux-x11


