# osr-infra

#### Running Ansible
After configuring the project, run the `ansible-playbook` command to apply the roles and confgs to the production server.

```sh
ansible-playbook -i inventory/production playbooks/build.yml -v --diff
```
