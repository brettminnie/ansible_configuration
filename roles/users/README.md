```yaml
system_users:
  - user_name: foo
    createhome: True # optional, default true
    shell: /bin/bash # optional default /bin/bash
    system: False # optional default false
    groups:
        - foo
        - wheel
        - admin
    state: present
    public_keys: # optional
        - key 1
        - key 2
```
