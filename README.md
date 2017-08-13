# ansible-repo

 ansible-playbook  -i inventories/staging/ --extra-vars "target=docker2 ansible_become_pass=f" site.yml  --tags "base-packages" --check
 ansible-playbook  -i inventories/staging/ --extra-vars "target=docker2 ansible_become_pass=f" site.yml  --tags "base-packages" --list-hosts
 ansible-playbook  -i inventories/staging/ --extra-vars "target=docker2 ansible_become_pass=f" site.yml  --tags "apache2" --check
