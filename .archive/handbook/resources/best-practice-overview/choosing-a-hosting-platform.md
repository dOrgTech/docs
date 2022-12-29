# Choosing a hosting platform

There are numerous hosting and deployment services available online that can run your app from. Below is a comparative list of the most typically used at dOrg:

### Netlify

{% embed url="https://www.netlify.com/" %}

Best for:

* Front end/React applications

Pros: 

* Very fast/easy configuration for hosting and DNS
* Free SSL
* Automatic deployment of PRs on staging site without needing a CI/CD
* Automated deployments without needing a CI/CD
* Serverless functions

Cons:

* Doesn't have Docker support
* Doesn't support Database management \(except for their own FaunaDB\)

Beware:

* For CRA Applications to work properly with React Router: [https://stackoverflow.com/a/55990523](https://stackoverflow.com/a/55990523)

### Heroku

{% embed url="https://www.heroku.com/" %}

Best for:

* Dockerized applications
* Database hosting

Pros:

* Very fast/easy configuration for hosting and DNS
* Docker support
* Automated deployments, even with Docker, without needing a CI/CD
* Database management

Cons:

* Its free tier "sleeps" when idle. That means that your hosted application will have downtime, don't use this plan on production
* No serverless functions
* No automated PR deployment

Beware:

* Free tier's sleep
* For CRA Applications to work properly: [https://stackoverflow.com/questions/50327645/deploy-production-of-create-react-app-to-heroku-without-buildpacks](https://stackoverflow.com/questions/50327645/deploy-production-of-create-react-app-to-heroku-without-buildpacks)

### Vercel

[https://vercel.com/](https://vercel.com/)

Best for:

* NextJS applications

Pros:

* Very fast/easy configuration for hosting and DNS
* Out of the box support for NextJS
* Automatic deployment of PRs on staging site without needing a CI/CD
* Automated deployments without needing a CI/CD
* Serverless functions

Cons:

* No docker or database support

### AWS

{% embed url="https://aws.amazon.com/" %}

Best for:

* Application with multiple docker files, or with docker-compose
* A very custom infrastructure is needed \(multiple dbs, or apis\)

Pros:

* No limits, can set up any services you want

Cons:

* It is not really easy to use so you need to educate yourself in order to use it
* Paid service
* You need to manually configure CI with Github Actions or any other CI/CD pipeline

