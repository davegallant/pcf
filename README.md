# pcf

pcf (proxmox container fuzzy) is a fuzzy finder for Proxmox LXC containers. It wraps the pct command, simplifying management of your proxmox lxc containers.

## Dependencies

```bash
apt install fzf
```

## Install

```sh
curl -fsSL https://raw.githubusercontent.com/davegallant/pcf/refs/heads/main/pcf | install -m 755 /dev/stdin /usr/local/bin/pcf
```
