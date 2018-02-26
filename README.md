# homelab

This project contains the running and bootstrap config for a Lenovo W530 running Fedora 27.  The intent is that this is pulled hourly (?) via cron and run with Ansible Tower.  We'll see.

Right now, run it locally via `ansible-playbook -i hosts w530-init.yml`
