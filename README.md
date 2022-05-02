os_release: Ansible Role
================================================================================

Grabs and parses the contents of /etc/os-release.

This file holds additional information that may not be provided by the setup
module. For example, if we wanted to know whether or not a host has Manjaro
installed, it is not easy to figure this out from the setup module. The setup
module produces `ansible_distribution=Archlinux` while this role produces
`os_release.ID=manjaro`.

License
----------------------------------------

GPL-3.0

