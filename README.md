# LAB: OAuth with GitHub (12b)

## Deploy an Express server that implements Basic Authentication, with signup and signin capabilities, using a Mongo database for storage.

### Author: Earl Jay Caoile

### Links and Resources

- [submission PR](https://github.com/js-401n15-eoc/lab-12b/pull/1)
- [GitHub Actions](https://github.com/js-401n15-eoc/lab-12b/actions)

#### Documentation

- [GitHub - Creating an OAuth App](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)

### Setup

#### Configuring MongoDB

- create an .env file on the top level of this repo defining the following variables:

```
MONGODB_URI=mongodb://localhost:27017/lab-12b
PORT=3000
```

- start your database with the path of the DB along with the folder location for your DB files (`mongod --dbpath=/Users/path/to/data/db`: i.e. `"C:\Program Files\MongoDB\Server\4.2\bin\mongod.exe" --dbpath="D:\db"`)

#### Tests

- Testing command: `npm test` from root directory

#### UML

![UML Image](lab-12a-UML.png 'uml diagram')
