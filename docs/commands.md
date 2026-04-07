# Useful Commands

## Mount NAS Command NOTE:(YOU HAVE TO MOUNT EVERY TIME BEFORE UPLOADING FILE IN PC.)
sudo mount -t cifs //<your IP address>/share /mnt/nas -o username=wick

## Backup Command
rsync -av /home/username/your target directory/ /mnt/nas/backup/

## Firewall Command
sudo ufw allow 445
sudo ufw allow 8096
