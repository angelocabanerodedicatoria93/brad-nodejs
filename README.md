# Node.js Crash Course

## traversy media

README.md

.gitignore

.editorconfig

```bash
git init
npm init -y

npm install eslint --save-dev
npx eslint --init
npx eslint yourfile.js
```

javascript runtime (not a language or a framework)

built on the v8 javascript engine (same as google chrome)

written in c++

essentially allows us to run javascript code on the server

### javascript fundamentals (objects, arrays, conditionals, etc)

> it may help to learn these first

* http (status codes, headers, etc)
* json
* arrow functions
* promises
* mvc pattern

non-blocking i/o model
nodes' event loop

## best types of projects for node

* rest api & microservices
* real time services (chat, live updates)
* crud apps - blogs, shopping carts, social networks
* tools & utilities

short answer: anything that is not cpu intensive

```bash
node --version
npm --version
node
```

```javascript
1+1
const name = 'brad'
name
console.log(name)
function hello() { return 'hello ' + name}
hello()
```

```bash
npm init
npm install uuid
npm install nodemon -D
delete node_modules
npm install
```

```bash
node index.js
node index
```

https://nodejs.org/dist/latest-v12.x/docs/api/path.html

```bash
node path_demo
```

https://nodejs.org/dist/latest-v12.x/docs/api/fs.html

```bash
node fs_demo
node os_demo
node url_demo
node event_demo
```

```bash
node http_demo
node index
```

localhost:5000
localhost:5000/about

```bash
nodemon index
```

```bash
npm run dev
```

localhost:5000

ctrl+u

developer tools, network, localhost, refresh if no display

 headers, content-type

localhost:5000/about

localhost:5000/api/users

### build file path

localhost:5000/

localhost:5000/about

### deployment in heroku

https://www.heroku.com/
heroku cli
download and install

```bash
heroku --version
heroku login
```

https://git-scm.com
download and install

```bash
git version
```

```bash
.gitignore
 node_modules
 reference
 logger.js
 person.js
git init
git add .
git commit -m 'initial commit'

heroku create
```

https://dashboard.heroku.com/apps
click domain name
 deploy

```bash
heroku git:remote -a enigmatic-island-05540
git push heroku master
heroku open
```
