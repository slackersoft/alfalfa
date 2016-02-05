# alfalfa

Experimental project for provisioning new machines that is more robust than
[shell scripts][workstation-setup] and less complicated than [chef
solo][sprout-wrap].

[workstation-setup]: https://github.com/pivotal/workstation-setup
[sprout-wrap]: https://github.com/pivotal-sprout/sprout-wrap

# Usage

```
brew install ansible
cd ansible
ansible-playbook main.yml --ask-pass --ask-become-pass
```
