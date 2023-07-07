# Next.js-Express-Server

Here is starter cheat sheet to run Express server in Next.js


# How To Use

1. Install Next.js
   Run : npx create-next-app@latest
   Source : https://nextjs.org/docs/getting-started/installation

2. Install Express
   Run : npm i express
   Source : https://www.npmjs.com/package/express

3. Install Nodemon
   Run : npm i nodemon
   Source : npmjs.com/package/nodemon

5. Install Body Parser
   Run : npm i body-parser
   Source : https://www.npmjs.com/package/body-parser

6. Create file "server.js" in the main directory of your app dir the same level where package.json is located
7. Open / click, copy and paste the code from this repo "server.js .
8. go to package.json from your main app directory and find "scripts" from the object then change the dev and start value to this code below
   
   "scripts": {
    "dev": "nodemon server.js",
    "build": "next build",
    "start": "NODE_ENV=production node server.js",
    "lint": "next lint"
  },

9. Finish, you can run your next app by run "npm run dev" it will connect to http://localhost:3000/
