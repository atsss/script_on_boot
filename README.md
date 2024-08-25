# script_on_boot
## How to use
1. sudo systemctl daemon-reload
2. sudo systemctl enable say-ready.service
3. sudo systemctl start say-ready.service
4. sudo systemctl stop say-ready.service
5. journalctl -u say-ready.service
