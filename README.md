# Project 

[![Alt text](https://img.youtube.com/vi/lXk14qt2D28/0.jpg)](https://www.youtube.com/watch?v=lXk14qt2D28)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

NPM / Yarn and Node.js installed

### .env

In the server > .env file
```
BRAINTREE_MERCHANT_ID=your_id
BRAINTREE_PUBLIC_KEY=your_public_key
BRAINTREE_PRIVATE_KEY=your_private_key
```

### Installing

Installing NPM modules on both client and server folders

Execute these commands from the project directory

```
cd client && npm install
```

```
cd server && npm install
```

### Running the app

Open a terminal on server directory

```
npm run start:dev
```

and open another terminal on client directory

```
npm run start
```

Access the web app at http://localhost:3000/


   `DATABASE=mongodb+srv://myusername:myclusterpassword@mycluster.mongodb.net/ecommerce?retryWrites=true&w=majority`
   you can find the mongo url by goto the mongodb atlas website and goto your database and you can find a connect button and click on that you will see the url. And modify the url quite like my one with your secret info.
   N.B: And you must need to provide the cluster password not your account password! So find your cluster password from database access menu in mongodb atlast cloud and change accoding to you. Here I provide all image's :
   ![Alt Text](assetREADME.md/atlasUrl.png)
   ![Alt Text](assetREADME.md/clusterPassword.png)
   ![Alt Text](assetREADME.md/networkAccess.png)


Thanks


