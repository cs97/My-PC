# My-PC


### sway status
* git clone https://github.com/cs97/rusty-sway-status
* cd rusty-sway-status
* cargo build --release --features battery-status
* cp target/release/status /usr/bin/status

### AMD GPU OC UV...
/etc/default/grub
```
GRUB_CMDLINE_LINUX_DEFAULT="... amdgpu.ppfeaturemask=0xffffffff"
```
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```



