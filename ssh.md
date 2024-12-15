# ssh private key with systemd

## run service

```bash
# enable and start service
systemctl --user enable ssh-agent.service
systemctl --user start ssh-agent.service

# check service is up
systemctl --user status ssh-agent.service
```

## add to .bashrc
```
export SSH_AUTH_SOCK=$XDG_RUNTIME_DIR/ssh-agent.socket
```
```bash
# reload config
source ~/.bashrc
```

## add to agent
```bash
# add private key to agent
ssh-add ~/.ssh/id_rsa
```
