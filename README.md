# ansible-examples
Common ansible examples and proof-of-concepts

### module && inventory (physical hosts)
    
    $ cd <repo_dir>/basics
    $ ansible -i inventory.yml -m debug -a "msg='Hello, world!'" all

### playbook && variables 
    
    $ cd <repo_dir>/basics
    $ ansible-playbook -i inventory.yml hello-world-multi.yaml

