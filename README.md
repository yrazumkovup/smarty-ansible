# smarty-ansible

## This repository contains ansible playbook to configure remote smarty server.

Here is the example how **DRY-RUN** might be performed for platform role:
```ansible-playbook -i inventories/dev.yml site.yml --tags "platform" --check```

To perform deployment to remote server we should remove --check flag:
```ansible-playbook -i inventories/dev.yml site.yml --tags "platform"```

**DRY-RUN** should be performed before creating each MR
