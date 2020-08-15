# ansible-role-sbt

#### Overview
 This will initialize yum with the base repo for the sbt project and then install the version of yum desired. 

#### Default values
```
---
sbt_version: 0.13.16-0
```

#### Sample playbook
```
---
- hosts: localhost
  roles:
  - role: ansible-role-sbt
  ```