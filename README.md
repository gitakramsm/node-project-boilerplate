To setup the project:
(if you are using node v 22, else scroll down)
step-1. Clone the project

```
git clone https://github.com/gitakramsm/node-project-boilerplate.git
```

step-2. Move in the directory where project is coded and cloned

```
cd node-project-boilerplate
```

step-3. Install dependencies

```
npm install
```
step-4. In the root directory create a .env file and add the following env variables

    PORT=<port number of your choice>
ex:

    PORT=3000

step-5. Turn up the server

```
node index.js
```

---Incase if you are below node version 22---

do this after step 2

  -> npm i nodemon

  -> replace the below line in package.json
    "scripts": {
        "dev": "node --watch ./src/index.js"
    },
    with
    "scripts": {
        "dev": "npx nodemon ./src/index.js"
    },

  then do step 3,4 and 5.


[note: nodemon is a package that automatically restarts the server after changes.]