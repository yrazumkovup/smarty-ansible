# smarty-ansible

## This repository contains ansible playbook to configure remote smarty server.

Here is the example how **DRY-RUN** might be performed for platform role:
```ansible-playbook -i inventories/dev.yml site.yml --tags "platform" --check```

**DRY-RUN** should be performed before creating each MR
