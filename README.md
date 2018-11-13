# ansible-workstation-fedora

This is an ansible playbook I created for easy deployment of my Fedora Workstation.

Xfce desktop environment using bspwm as a tiling window manager. A little bit of theming to make things look nice.

Included a task for deploying QEMU/KVM including tweaks to make GPU passthrough possible and play nice with Windows 10.

Barrier is a software kvm for my keyboard and mouse between my Fedora host and Windows guest.

Replacing xfwm with bspwm can be a bit of a pain, check xfce-settings task to see what I mean.

Everything else is fairly standard and broken down by task.

# Installed Tools (dependencies not listed)
- barrier
- bash-it
- bspwm
- chrome
- compton
- nvim
- qemu
- rofi
- sxhkd
- vmware

## Example Screenshots
![Example Lockscreen]()
![Example Desktop]()
![Example Terminal]()
