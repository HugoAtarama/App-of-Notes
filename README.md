#App NOtes
This is an application to manage your time using notes

This app can do:

- CRUD Operations: create/read/update/delete Notes
- Allows a user to do login and save his personal notes

### Installation

```sh
git clone https://github.com/HugoAtarama/Project-notes.git
cd nodejs-notes-app
npm i
npm run dev # run in development mode
npm start # run in production mode
```

> You need to have Mongodb installed Locally or stablish a MONGODB_URI environment variable in order to connect to any mongodb instance 
### Environment Variables

This app needs the following environment Variables

- `MONGODB_URI` this is the Mongodb URI string
- `PORT` the server http port for the application
- `NODE_ENV` node environment

### Default User

credentials:

- email: `hugo_atarama@gmail.com`
- password: `adminpassword`