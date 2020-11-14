<h1 align="center">Welcome to Ansible 👋</h1>
<p>
  <img src="https://img.shields.io/badge/version-2.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="http://coursenux.com">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
</p>

### 🏠 [Homepage](https://coursenux.com)

## Author

👤 **Coursenux Tech**

Example commands running from `./playbooks`

```
# Running playbooks

cd playbooks
ansible-playbook -i inventories/server.ini coursenux.yaml --check

# Ping Ansible Command

cd playbooks
ansible -i inventories/server.ini tag_Hostgroup_coursenux -m ping
```

## Requirements

Ansbile version

- `> 2.9.2`

Python version

- `> 3.7`

See in ./playbooks/requirements.txt for the details

## Attention

- Please don't commit and push credential here (Contact the Coursenux team to encrypt secrets using ansible vault)
- Always use `Pull Request` to commit changes
- Variables and Tags must be in the correct format: `<ROLE_NAME>_<TAG_NAME>` to avoid conflicts across different roles.
(e.g. `redis_the_redis_variable`)
- Always use **UNDERSCORES** (`_`) in role, variable, and hostgroup names.
- Playbook's file names should be dash separated (e.g. `redis-platform.yaml`)

If you have questions/suggestions to about Vagrant setup, feel free to contact the **Coursenux** team.

