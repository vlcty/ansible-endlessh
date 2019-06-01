# ansible-endlessh

Deploys a precompiled endlessh binary and creates a systemd servic file for it. Endlessh is a ssh tarpit. Trapping bots for some times.

This role:

- Deploys a precompiled binary
- Creates a systemd service file
- Starts endlessh on IPv4 interfaces only on port 22

You can see the log using `journalctl -u endlessh --follow`.

Project homepage: https://github.com/skeeto/endlessh
