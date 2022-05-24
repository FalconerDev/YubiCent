# YubiCent
This is the raw playbook for ansible to install the epel repository and pam_yubico package for RHEL based systems.  PLEASE NOTE: This uses YUM and has been tested GOOD on CentOS 7.  I will update this later to confirm this playbook is compatible with CentOS (stream) 8.

Nota Bene: I have not included the edits to the configuration file to acitvely use your YubiKey because that requires an API key unique to you.  I'm not in the business of giving MY API key out, so, you will need to setup your YubiKey as per your operational standards.

To execute (from within the same directory as your hosts file): "ansible-playbook -i [hosts file] prep_yubi.yml"
