# add-sudo-user

This repo is a playbook that adds sudo users to a debian Linux system.

This was specifically used for Cumulus Linux to add local users in an automated way.

## Managing users
Edit the variables dictionary:
```
  vars:
    users: ["cumulus"]
```

## Running the playbook
Execute the playbook on the hosts:
```
ansible-playbook add-sudo-user.yml
```