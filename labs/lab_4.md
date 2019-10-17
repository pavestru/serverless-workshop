## Lab 4

Connect the frontend with Notes API and deploy it using serverless.

### Prerequisities

1. Clone the frontend: `git clone https://github.com/pavestru/serverless-workshop-frontend`
2. `npm install`

### Configure and test locally

1. Change values in `src/config.js` to match the Notes API deployment
1. Run `npm start`
1. Create user by signing up
1. Login, create notes...

### Deploy to S3 public bucket

1. Build frontend: `npm run build`
1. Follow Serverless [website component](https://github.com/serverless-components/website#3-configure) README to deploy the frontend to S3.
