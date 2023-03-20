# delta-ansible-deploy
Ansible tooling for automatically deploying Delta to infrastructure of your choice (thanks for using Delta!)

To use:
* Check out this repo after making sure you've installed Ansible 2.12+
  `git clone https://github.com/application-research/delta-ansible-deploy`

* Copy `vars/settings.yml.dist` to `vars/settings.yml`
  `cp vars/settings.yml.dist vars/settings.yml`

* Edit `inventory` and fill out the machine list

* Install dependencies
  `ansible-galaxy install -r requirements.yml`

None of these steps will need repeating once you've done them once (unless you want to update dependencies or settings or they change).

Now you're ready. Go!

* ansible-playbook site.yml

Ask in #ecosystem-dev if you have any questions, and enjoy!

# TODOs/roadmap
* Add Docker deployment option, bare metal mode will be the default for now (and probably a long time, slightly more efficient I/O)