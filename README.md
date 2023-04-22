# delta-dm-playbook
Ansible tooling for automatically deploying Delta DM to infrastructure of your choice. Pairs well with Delta Playbook.

## Getting started

* Check out this repo after making sure you've installed Ansible 2.12+

`git clone https://github.com/application-research/delta-ansible-deploy`

* Edit the default inventory file (`inventories/dev`) and list one or more machines you want to deploy to

* Install dependencies

`ansible-galaxy install -r requirements.yml`

None of these steps will need repeating once you've done them once (unless you want to update dependencies or they change).

* Run the playbook

`ansible-playbook deploy.yml`

Ask in [#ecosystem-dev](https://filecoinproject.slack.com/archives/C016APFREQK) if you have any questions, and enjoy!
