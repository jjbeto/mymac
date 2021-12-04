# Ansible

Ansible is an infrastructure automation tool initially developed by RedHat. 

## Use cases:

- Provisioning
  - Inventory
    - Parents
    - Children
  - Uses provided tasks and roles to provision on many cloud envs

- Config Management: configure your infrastructure
  - Tasks with Operations
    - OS patches
    - Package installations
  - Ansible is `Declarative` & `Imperative`: you declare what you want not knowing how to get there, while underlying tasks running are imperative
  - Playbooks: group of tasks that would be executed on a group of hosts
  - `Agent-less`: no agent is necessary on target hosts, operations can be done via ssh
  - `Idenpotent`: can run multiple times, just changes steps that is necessary
  - `Community Driven`: ansible-galaxy

- App deployment
