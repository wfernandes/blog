Simple Blog
===========

### Deployment
```bash
# At the root level of the project
hugo
cd public
cf push <app_name> -b staticfile_buildpack
```
