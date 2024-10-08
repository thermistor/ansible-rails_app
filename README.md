# rails_app

An ansible galaxy role for configuring a rails app.

## Tags

`vhost` - Redeploy the vhost config and restart nginx

## Caveats

- it's opinionated
- assumes using `capistrano-git_deploy` gem for deployment
- ssl certs are created outside of this role, but default paths conform w/ `thermistor.nginx` and `thermistor.acme_sh`
