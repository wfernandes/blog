Simple Blog
===========

### Website
The website can be located at
[wfernandes.cfapps.io](http://wfernandes.cfapps.io)

### Deployment
```bash
# At the root level of the project
hugo
cd public
cf push <app_name> -b staticfile_buildpack
```
