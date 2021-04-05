1. Initialize CDK:
> cdk init app --language=typescript

2. To run test
> npm test

3. Install Bootstrap toolkit
> cdk bootstrap

4. List all stacks
> cdk list

5. Deploy stack
> cdk deploy

6. Install a new dependency:
> npm install @aws-cdk/aws-s3@1.92.0

7. Open CDK docs:
> cdk doc

8. See difference between current infra and code:
> cdk diff

9. To generate cloudformation template:
> create templates folder
> cdk synthesize --output=./templates

10. Package for testing:
> npm install @aws-cdk/assert

11. Install nodejs construct for nodejs lambda:
> npm install @aws-cdk/aws-lambda-nodejs
> add "esModuleInterop": true in jscofig.json - It allows to use import instead of require.

12. install package.json and node_modules for api sub-module project.
> cd api/get-photos
> npm install -y
>npm install -D @types/aws-lambda aws-sdk

13. Run: It wil build docker image
> cdk diff
> cdk deploy
> npm install @aws-cdk/aws-s3-deployment@1.92.0

14. Install aws-iam to allow lambda access to s3 bucket.
> npm install @aws-cdk/aws-iam@1.92.0

15. Install npm package for API Gateway
> npm install @aws-cdk/aws-apigatewayv2@1.92.0
> npm install @aws-cdk/aws-apigatewayv2-integrations@1.92.0
> cdk deploy

16. Create react App
> npx create-react-app frontend --temlate typescript
> cd frontend/
> yarn start
> Create a file .env and add 'SKIP_PREFLIGHT_CHECK=true'
> yarn build

17. Install cloudfrobt pakage.
> npm install @aws-cdk/aws-cloudfront@1.92.0
> cdk deploy

18. Go to frontend package and install some modules
> yarn add axios react-bootstrap bootstrap

