# Indecision app

> :warning: This project is archived and no longer supported. Associated Heroku deployment has been removed.

![CI](https://github.com/fabasoad/indecision-app/workflows/CI/badge.svg) ![Security Tests](https://github.com/fabasoad/indecision-app/workflows/Security%20Tests/badge.svg) ![YAML Lint](https://github.com/fabasoad/indecision-app/workflows/YAML%20Lint/badge.svg) [![Total alerts](https://img.shields.io/lgtm/alerts/g/fabasoad/indecision-app.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/fabasoad/indecision-app/alerts/) [![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/fabasoad/indecision-app.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/fabasoad/indecision-app/context:javascript) [![Maintainability](https://api.codeclimate.com/v1/badges/b4121503ccd8561e1fc5/maintainability)](https://codeclimate.com/github/fabasoad/indecision-app/maintainability) [![Known Vulnerabilities](https://snyk.io/test/github/fabasoad/indecision-app/badge.svg)](https://snyk.io/test/github/fabasoad/indecision-app) ![GitHub repo size](https://img.shields.io/github/repo-size/fabasoad/indecision-app)

## Description

Indecision app that is developed in scope of Udemy [The Complete React Developer Course (w/ Hooks and Redux)](https://www.udemy.com/course/react-2nd-edition/) course.

## Technologies

1. React
1. Webpack
1. Babel
1. SCSS

## How to run app locally

```bash
git clone git@github.com:fabasoad/indecision-app.git
cd indecision-app
yarn install
yarn run start:dev
```

Go to <http://localhost:8080/> and be sure that app is running.

## How to deploy to Heroku

- Install Heroku CLI.
- Run the following commands:

```bash
git clone git@github.com:fabasoad/indecision-app.git
cd indecision-app
heroku login
git remote add heroku https://git.heroku.com/fabasoad-indecision.git
git push heroku master
```

- Go to <https://fabasoad-indecision.herokuapp.com/> and be sure that up-to-date version of an app is deployed.
