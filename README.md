# sftp

## References

https://linuxconfig.org/how-to-setup-sftp-server-on-ubuntu-18-04-bionic-beaver-with-vsftpd

https://superuser.com/questions/1417082/how-do-i-setup-ftp-sftp-on-aws

https://help.ubuntu.com/community/SSH/OpenSSH/Configuring#:~:text=LogLevel%20VERBOSE,level%20and%20examine%20your%20auth.

#### Subsystem sftp internal-sftp
>https://serverfault.com/questions/660160/openssh-difference-between-internal-sftp-and-sftp-server

#### Cyptography
>https://www.ssh.com/ssh/sshd_config/#:~:text=The%20ciphers%20supported%20in%20OpenSSH,%2Dpoly1305%40openssh.com%20.


#### Create hash password using openssl
https://ma.ttias.be/how-to-generate-a-passwd-password-hash-via-the-command-line-on-linux/

#### RUN
> ansible-playbook ssh_config.yaml
> ansible-playbook sftp.yaml


#### Provide a folder access to use
> Create sub-directory in chroot directory
> Make sure 755 permission /sftp bcz `/sftp/product1` and `/sftp/product2` will accessed by sftp users.
