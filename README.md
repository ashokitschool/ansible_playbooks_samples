# ANSIBLE_PLAYBOOKS Commands

# Run the playbook Using below command

$ ansible-playbook playbook.yml

# run the playbook.yml in verbose

$ ansible-playbook playbook.yml -v
$ ansible-playbook playbook.yml -vv
$ ansible-playbook playbook.yml -vvv

$ It will provide help on ansible_playbook command
$ ansible-playbook --help

#  It will check the syntax of a playbook
$ ansible-playbook playbook.yml --syntax-check

# It will do in dry run.
$ ansible-playbook playbook.yml --check

# It will display the which hosts would be effected by a playbook before run
$ ansible-playbook playbook.yml --list-hosts

# It execute one-step-at-a-time, confirm each task before running with (N)o/(y)es/(c)ontinue
$ ansible-playbook playbook.yml --step
