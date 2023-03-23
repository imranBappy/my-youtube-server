# my-youtube-json-server-todos

Example in memory todos api with json-server by Imran Hossen

# Installation

```bash
git https://github.com/imranBappy/my-youtube-server.git
cd my-youtube-server
npm install json-server
npm start
```

Now opens:

- http://localhost:3000

You now have a full REST API. Test with POSTMAN or any other REST Client):

Retrieve all (GET):

```bash
GET http://localhost:3000/todos
```

Retrieve one (GET):

```bash
GET http://localhost:3000/todos/1
```

Post a todo (POST):

```bash
POST http://localhost:3000/todos text="Learn Redux" completed=false color="red"
```

Update todo (PUT):

```bash
PUT http://localhost:3000/todos/3 name="Learn Redux with Learn with Sumit" completed=true color="green"
```

Delete todo (DELETE):

```bash
DELETE http://localhost:3000/todos/1
```