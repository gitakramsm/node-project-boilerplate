To setup the project:

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

step-4. Turn up the server

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

  then do step 3 and 4.


[note: nodemon is a package that automatically restarts the server after changes.]