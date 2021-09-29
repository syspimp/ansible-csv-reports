# ansible-csv-reports

This creates a report on your infrastructure. Modify the report templates to extract the information you need. Use this URL for reference [https://docs.ansible.com/ansible/latest/user_guide/playbooks_vars_facts.html]

To test against localhost

```
ansible-playbook -i 'localhost,' -c local ./make-inventory-report.yml 
```


