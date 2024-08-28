# diyrotate-playbooks
## role to deploy the latest version of the DIYROTATE CODE ##


For deployment on the dev site, run:
```
ansible-playbook dpr-prod-deploy.yml -f 10 -e host_override=localhost
site_fqdn=dpr-dev.epss.ucla.edu
```
