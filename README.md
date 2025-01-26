Mount disk:
sudo mount /dev/sda1 /mnt

Setup samba, bottom of file:
`sudo nano /etc/samba/smb.conf`

Optional:
`sudo smbpasswd -a pi`
`sudo systemctl restart smbd`  

External storage mounted in /etc/fstab, copy of file in repo.
Note: permissions need to be set during mounting, otherwise changing file permissions may be denied, so fstab is needed. 
