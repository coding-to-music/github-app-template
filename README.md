# github-app-template

# 🚀 GitHub App Template for Auth with Ruby 🚀

### GitHub App Template for Auth with Ruby

https://github.com/coding-to-music/github-app-template

https://github-app-template.herokuapp.com

by

https://docs.github.com/en/developers/apps/getting-started-with-apps/setting-up-your-development-environment-to-create-a-github-app

You can use this GitHub App template code as a foundation to create any GitHub App you'd like. You can learn how to configure a template GitHub App by following the "[Setting up your development environment](https://developer.github.com/apps/quickstart-guides/setting-up-your-development-environment/)" quickstart guide on developer.github.com.

## Install

To run the code, make sure you have [Bundler](http://gembundler.com/) installed; then enter `bundle install` on the command line.

## Set environment variables

1. Create a copy of the `.env-example` file called `.env`.
2. Add your GitHub App's private key, app ID, and webhook secret to the `.env` file.

## Run the server

1. Run `ruby template_server.rb` on the command line.
1. View the default Sinatra app at `localhost:3000`.

https://smee.io/

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/github-app-template.git
git push -u origin main
```

## deploy:

```java
git add . && git commit -m Build && git push
```
