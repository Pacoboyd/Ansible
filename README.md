Git for Ansible playbooks

ubuntu_patching.yml

  This cleans the apt repository, auto removes unused packages, and performs a full dist upgrade.  Peforms reboot if needed.
  
wg_status.yml

  Checks the status of WireGuard after an update, recomplies the kernel module if needed and restarts WireGuard.
  
windows_patching.yml

  This lists the currently installed windows updates then performs a patch to current.  Performs a reboot if needed.
