[![CI](https://github.com/de-it-krachten/ansible-role-test/workflows/CI/badge.svg?event=push)](https://github.com/de-it-krachten/ansible-role-test/actions?query=workflow%3ACI)

# ansible-role-test

<basic role description>



## Dependencies

#### Roles
None

#### Collections
None

## Platforms

Supported platforms

- Red Hat Enterprise Linux 8<sup>1</sup>
- RockyLinux 8

Note:
<sup>1</sup> : no automated testing is performed on these platforms

## Role Variables
### defaults/main.yml
<pre><code>
var1: toos
</pre></code>




## Example Playbook
### molecule/default/converge.yml
<pre><code>
- name: sample playbook for role 'test'
  hosts: all
  become: 'yes'
  tasks:
    - name: Include role 'test'
      ansible.builtin.include_role:
        name: test
</pre></code>
