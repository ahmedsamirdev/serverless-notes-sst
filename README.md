# Serverless-stack Notes App

This project was bootstrapped with [Create Serverless Stack](https://docs.serverless-stack.com/packages/create-serverless-stack).
</br>

### Tech stack

- React.js
- AWS Lambda
- API Gateway
- DynamoDB
- Cognito
- React Bootstrap</br>

### **Features**

- Login with email address and receive confirmation number.

- Upload files to your note.

- Delete, list all your notes.

- Buy more storage space for your notes by process credit card payments with Stripe.

  

### Usage

Clone this repo.

```
git clone https://github.com/serverless-stack/demo-notes-app
```

Install dependencies.

```
npm install
```

This project refers to a `.env.local` file with a secret that we are not checking in to the repo. Make sure to create one before deploying.

#### Developing Locally

Start the [Live Lambda Dev Environment](https://docs.serverless-stack.com/live-lambda-development).

``` 
npx sst start
```

Install dependencies for the frontend React app.

``` 
cd frontend
npm install
```

Start the React local dev environment from the `frontend/` dir.

``` 
npm start
```

#### Running Tests

From the project root.

``` 
npx sst test
```

#### Deploying to Prod

Run this in the project root to deploy it to prod.

``` 
npx sst deploy
```


[Live Preview](https://d3rxr44trvkza4.cloudfront.net/)
