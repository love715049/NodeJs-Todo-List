## Project setup
This app contains both the backend and the frontend in a single repository.
```	
├── Readme.md
├── backend
├── docker-compose.yml
└── frontend
```

### Clone Repository

```bash
git clone git@github.com:love715049/NodeJs-Todo-List.git
```

Navigate to the root directory.

```bash
$ cd NodeJs-Todo-List
```
### Start app containers

Start the `frontend`, `backend` and `db` containers using docker-compose

```	bash
$ docker-compose up -d 
```
Access the app from your browser at http://localhost:8080

### Reference 
Build a Todo App with Node.Js, ExpressJs, MongoDB and VueJs 
[Part 1](https://dev.to/abiodunjames/build-a-todo-app-with-nodejs-expressjs-mongodb-and-vuejs--part-1--29n7)
[Part 2](https://dev.to/abiodunjames/build-a-todo-app-with-nodejs-expressjs-mongodb-and-vuejs--part-2--3k11)