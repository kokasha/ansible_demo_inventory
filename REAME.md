# HOWTO

In order to run the playbook we must supply `app_name` as an extra var in order to load the correct group and its associated varaibles

```
ansible-playbook pb.deploy_app.yml -e app_name=<APP_NAME>
```