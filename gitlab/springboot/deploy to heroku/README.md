# Deploying your springboot application to heroku using gitlab pipeline

- [Setup Heroku](https://devcenter.heroku.com/start)

- Get variables

        HEROKU_API_KEY (can be seen in Account Settings -> API Key)

        HEROKU_APP_STAGING (the name of my heroku app for staging)

        HEROKU_APP_PRODUCTION (the name of my heroku app for staging)

- Set environment variables in gitlab
`Settings -> CI/CD -> Environment Variables`
- push code