todo: write some better docs

First run: ansible-playbook site.yaml -t initial,apt-update -e 'ansible_user=ubuntu' -k
Every other run: ansible-playbook site.yaml

