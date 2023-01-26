# Cisco Anyconnect CSD wrapper for OpenConnect

# Setting wrapper
```bash
mkdir -p ~/.cisco
cp -L wrapper.sh ~/.cisco/wrapper.sh
```

# Use wrapper
```bash
openconnect your.vpn.com --user="yourName" --passwd-on-stdin --csd-wrapper="~/.cisco/wrapper.sh"
```
