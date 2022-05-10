# esm-for-solid

To mount VASP output from remote HPC cluster on Mac M1, use this command\
`sshfs 'username@remote_host:/path/to/file' '/Users/username/mnt' -o volname=desired_volume_name -o local`
