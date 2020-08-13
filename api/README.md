# Strapi application

A quick description of your strapi application

## Heroku Deploy

Using https://github.com/lstoll/heroku-buildpack-monorepo

Add buildpacks:

```bash
heroku buildpacks:add -a react-strapi-landing-page-api heroku/nodejs
heroku buildpacks:add -a react-strapi-landing-page-api https://github.com/lstoll/heroku-buildpack-monorepo
```

Deploy :rocket:

```bash
git push heroku master
```
