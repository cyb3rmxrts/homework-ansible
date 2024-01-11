Wednesday Homework
    
    Idempotence refers to the programs ability to recognize that a change has been made, and to not apply those same changes once again after initial execution. 

    This is helpful DevOps automation and configuration management because it allows us have predictability, repeatability, and state managemen within our workflow.

    Chef and Puppet are two other tools that are idempotent in the way that Ansible is.

    In the terminal below, we see Ansible's idempotence because I ran the playbook to add test.txt twice, but there's only one test.txt file in my directory because Ansible recognizes that this playbook already added the file.