# wordpress-mysql-nfs


Copy vm_hosts and  .vault_pass to top level



Copy vars, vault, backups to ./group_vars/all/


'''
ansible-playbook -i vm_hosts playbooks/wordpress-mysql.yml --vault-password-file .vault_pass
'''


'''
ansible-playbook -i vm_hosts playbooks/wordpress-mysql-teardown.yml --vault-password-file .vault_pass
'''


