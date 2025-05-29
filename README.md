# haproxy-ansible
automatization of haproxy installation\management


###structure

haproxy-ansible/
├── inventory/
│   └── hosts.yml
├── playbook.yml
└── roles/
    └── haproxy/
        ├── tasks/
        │   └── main.yml
        ├── templates/
        │   └── haproxy.cfg.j2
        ├── defaults/
        │   └── main.yml
        └── handlers/
            └── main.yml

