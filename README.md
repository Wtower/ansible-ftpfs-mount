ftpfs-mount
===========

Ansible role to mount a FTP site on filesystem using curlftpfs.

Add the role `ftpfs-mount`.

Variables:

- `ftp_mount_dir`: The directory on which to mount FTP
- `ftp_conn`: An FTP connection string, or alternatively:
- `ftp_user`
- `ftp_pass`
- `ftp_host`
- `ftp_path`
