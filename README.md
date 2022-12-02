# DecisionSciencesAnalyticsAssignment

Local installation:

```bash
# Clone this repository
```

---

**Server setup:**
```bash
# Change directory to the server path
$ cd server

# Install dependencies
$ npm install

```

server **.env** file setup:

```shell
PORT=5000
MONGODB_CNN=MONGO_DB_URL
JWT_SECRET_KEY=RANDOMKEY
```

---

**Client setup:**
```bash
# Go back to the project path
$ cd ..

# Change directory to the client path
$ cd client

# Install dependencies
$ npm install

```

client **.env** file setup:

```shell
REACT_APP_API_URL="http://localhost:5000/api"
```

## Deployment 📦

```bash
# Open terminal in project path and run
$ cd server
$ npm start


# Open another terminal in project path and run
$ cd client
$ npm start
```
