# salogel-server
Personal archlinux server setup.

Steps to setup:
- buy a VPS on Contabo
- choose to install a Custom Image
- select Archlinux as the image
- install
- set the host in the `hosts` file
- run the playbook(s) using `ansible-playbook run.yml`. FOr the first run (and the first run only), you'll need to pass `--ask-pass`as an additional option, which will prompt for the root password.
