# ENS for Red Hat Enterprise Linux 7

Ansible Role for ENS for Red Hat Enterprise Linux 7  

Profile Description:  
This profile contains configuration checks that align to the   
  ENS for Red Hat Enterprise Linux 7.   

## Requirements

- Ansible version 2.5 or higher

## Role Variables

To customize the role to your liking, check out the [list of variables](vars/main.yml).

## Dependencies

N/A

## Example Playbook

Then, you can use the following playbook snippet to run the Ansible role:

    - hosts: all
      roles:
         - { role: ens-ansible.rhel7_ens }

Next, check the playbook using (on the localhost) the following example:

    ansible-playbook -i "localhost," -c local --check playbook.yml

To deploy it, use (this may change configuration of your local machine!):

    ansible-playbook -i "localhost," -c local playbook.yml

## License

BSD-3-Clause

## Author Information

@gobispo and @jmperalb modified it but the original authors are https://github.com/complianceascode/content/blob/master/Contributors.md
