### description
This is a very simple cloud storage application. It allows you to register, upload, download and delete files.
The backend is written in express, the database is MongoDB, the frontend is written in react, react-redux, redux-thunk, react-router-dom.
**[Link to project on Heroku](https://ulbi-cloud-storage.herokuapp.com/)**

### cloning

```
$ git clone --recurse-submodules https://github.com/DanielShtrasser/CloudStorage.git
```

### install

```
.../client$ npm install
```
```
.../server$ npm install
```

### run
```
.../client$ npm run start
# started on process.env.PORT || 8080
```

```
.../server$ npm run start
# started on process.env.PORT || 5000
```