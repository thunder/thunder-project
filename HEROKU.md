
## Deployment to heroku

Create a composer.lock by running `composer install`; Add composer lock file and commit it.

Create an heroku app using `heroku create:app <app-name> -r <app-name> --region=eu` and push local branch to heroku `git push <app-name> heroku:master`
