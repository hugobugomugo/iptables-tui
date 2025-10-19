# iptui
## nmtui inspired iptables tui


Make a backup of your iptables configuration before using this tool.

Use at your own risk.


### Install:
```
apt install iptables iptables-persistent fzf dialog
curl -L https://raw.githubusercontent.com/hugobugomugo/iptui/refs/heads/main/iptui -o /usr/local/bin/iptui
chmod +x /usr/local/bin/iptui
```

### Roadmap:
- [x] add multi delete function
- ~~[ ] implement fzf selection into dialog~~
- [ ] format "delete rules" to not break formatting
