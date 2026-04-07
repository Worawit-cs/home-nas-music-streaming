# Troubleshooting

## Jellyfin cannot see files
Cause: Permission issue

Fix:
sudo usermod -aG wick jellyfin
sudo chmod -R 775 /home/wick/share

---

## SMB Permission denied
Fix:
sudo chown -R wick:wick /home/wick/share
