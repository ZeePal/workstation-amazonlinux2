# ZeePal's Amazon Linux 2 in AWS Workspaces Installer
This repo is intended to provide an easy way of building my preferred workstation.

Installation is intended to run on a brand new installation of Amazon Linux 2 inside of AWS Workspaces.


## Lazy Installation
**DISCLAIMER:** I do not recommend using this method, its INSECURE!
```bash
wget -O - https://raw.githubusercontent.com/ZeePal/workstation-amazonlinux2/master/bootstrap_install | bash
```

## Safer Installation
```bash
wget -O /tmp/bootstrap https://raw.githubusercontent.com/ZeePal/workstation-amazonlinux2/master/bootstrap_install
less /tmp/bootstrap
# Use eyeballs to review :D
chmod +x /tmp/bootstrap
/tmp/bootstrap
```
