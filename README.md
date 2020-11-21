# Indecision app
![](https://github.com/fabasoad/indecision-app/workflows/CI/badge.svg) [![Total alerts](https://img.shields.io/lgtm/alerts/g/fabasoad/indecision-app.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/fabasoad/indecision-app/alerts/) [![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/fabasoad/indecision-app.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/fabasoad/indecision-app/context:javascript) [![Maintainability](https://api.codeclimate.com/v1/badges/b4121503ccd8561e1fc5/maintainability)](https://codeclimate.com/github/fabasoad/indecision-app/maintainability) [![Known Vulnerabilities](https://snyk.io/test/github/fabasoad/indecision-app/badge.svg)](https://snyk.io/test/github/fabasoad/indecision-app) ![GitHub repo size](https://img.shields.io/github/repo-size/fabasoad/indecision-app)
## Description
Indecision app that is developed in scope of Udemy [The Complete React Developer Course (w/ Hooks and Redux)](https://www.udemy.com/course/react-2nd-edition/) course.
## Technologies
1. React 16.11.0
3. Webpack 4.41.2
5. Babel 7.6.4
7. SCSS 8.0.0
## How to run app locally
```bash
git clone git@github.com:fabasoad/indecision-app.git
cd indecision-app
yarn install
yarn run start:dev
```
Go to http://localhost:8080/ and be sure that app is running.
## How to deploy to Heroku
1. Install Heroku CLI.
2. Run the following commands:
```bash
git clone git@github.com:fabasoad/indecision-app.git
cd indecision-app
heroku login
git remote add heroku https://git.heroku.com/fabasoad-indecision.git
git push heroku master
```
3. Go to https://fabasoad-indecision.herokuapp.com/ and be sure that up-to-date version of an app is deployed.
