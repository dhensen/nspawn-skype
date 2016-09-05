# What is this nspawn thing?
systemd-nspawn is a systemd utility that spawns a namespace container. I use it to contain Skype, because skype is proprietary software and thus can not be trusted.

# Requirements
- Arch linux
- (TODO: fix this) assuming your uid is 1000
- pulseaudio
- Xorg display server

# Usage
After cloning and cd'ing into resulting folder Run:
```
chmod u+x nspawn-skype
./nspawn-skype
```

# How can I improve this?
- If you are using another operating system that uses systemd (fedora, ubuntu, opensuse) you can make this script work by fixing the package installation inside the container. the rest should be trivial.

