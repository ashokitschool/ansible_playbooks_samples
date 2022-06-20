# Ansible Playbook Commands

# Run the playbook Using below command
$ ansible-playbook playbook.yml

# Run the playbook.yml in verbose
$ ansible-playbook playbook.yml -vvv

# Get Playbook helpful commands
$ ansible-playbook --help

# To check syntax of a playbook
$ ansible-playbook playbook.yml --syntax-check

# To execute playbook in dry run mode
$ ansible-playbook playbook.yml --check

# To display which hosts would be effected by a playbook before run
$ ansible-playbook playbook.yml --list-hosts

# To execute one-step-at-a-time and confirm each task before running with (N)o/(y)es/(c)ontinue
$ ansible-playbook playbook.yml --step
