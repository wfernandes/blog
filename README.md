Landing Page SIte
===========

### Website
The website can be located at [wfernandes.github.io][website]


### Notes
1. This project contains a submodule pointing to the repository,
   wfernandes.github.io
1. In order to verify the site locally, comment out the `publishDir` line in
   `config.toml` so that the contents can be published to the `public/` dir.
1. Once the site is verified, uncomment the `publishDir`

### Deploy
1. At the root level of the project, Run `hugo`
1. Since the `publishDir` is pointing to `wfernandes.github.io` in
   `config.toml`, the content of the site is published to the submodule.
1. `cd wfernandes.github.io`
1. `git add . && git commit -m "Update" && git push`
1. Don't forget to do the above step in this repository as well.
```


[website]: https://wfernandes.github.io
