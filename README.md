# Ansible post install playbook for CentOS 7/8
- Add packages (net-tools, iptables, iptables-services, wget, mc, nfs-utils, epel-release, zip, git)
- Install the latest kernel and open-vm-tools (reboot to apply changes)
- Update all packages
- Disable SELinux (reboot to apply changes)
- Disable ipv6 (reboot to apply changes)
- Disable and mask firewalld
- Enable and start iptables
- Enable UseDNS parameter for SSHd
- Setup automount nfs directory
