# dokku-setup

## Level 1: Use dokku as git remote manually
1. Buy a VM e.g. hetzner
2. Shell into VM (with SSH key)
   with `ssh root@IP -i private_key`
4. Install Dokku (follow [docu](https://dokku.com/docs/getting-started/installation/))
   - Create a second ssh key manually (this is just for git remote) - [here](https://dokku.com/docs/deployment/user-management/#adding-ssh-keys)
5. Create app in cli
6. Provide buildpack file to spring repo [link](https://devcenter.heroku.com/articles/deploying-gradle-apps-on-heroku#the-procfile)
7. Set dokku url as remote of github repo and push
   
## Level 2: Use Github Actions to automatically deploy to dokku
- you will need the SSH key of dokkus git backend

## Level 3: Setup custom domain, Use it for static site hosting etc.
