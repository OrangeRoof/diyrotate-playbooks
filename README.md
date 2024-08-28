# diyrotate-playbooks
## role to deploy the latest version of the DIYROTATE CODE ##


For deployment on the dev site, run:
```
rm -fdr /srv/diyrot && ansible-playbook dpr-prod-deploy.yml -f 10 -e host_override=localhost -e site_fqdn=dpr-dev.epss.ucla.edu
```
