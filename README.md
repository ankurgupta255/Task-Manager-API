# Task-Manager-API

This is an API based on a Task Manager App which can be used by anyone and everyone..

The API consists of two Models(User, and Task), It consists of a Signup/SingIn feature through which people can Log Into their accounts. Then they can use the app to create various Tasks and Update, Delete, Mark Completed as they Progress.

This API is written in Node.Js, Express.Js, Mongoose.Js and MongoDB.

## Prerequisites:

You do not need to clone the repository. The API is already deployed on Heroku and You can use it Directly from https://my-task-manager-api.herokuapp.com

## Utilities Provided by the API:

### Create a User with a Name, Age, Email, Password.

### SignIn feature for a User to Sign into the Dashboard.

### Edit, Delete, feature for User.

### Update Profile Image feature for User.

### Add Tasks for the User with a Description and Completion status.

### Edit, Remove, Mark Complete feature for the Tasks.

## How to Start:

Visit the API url given at the top of the Repo.

## How to Use:

## User Routes

### Creating a User:

Open `https://my-task-manager-api.herokuapp.com/users` with a POST Request with the User Details as shown in the User Model enclosed in a JSON Object

### Logging in as a User:

Open `https://my-task-manager-api.herokuapp.com/users/login` with a POST Request with the User Details as shown in the User Model enclosed in a JSON Object

### Logging Out as a User:

Open `https://my-task-manager-api.herokuapp.com/users/logout` with a POST Request

### Get Profile Detailes as a User:

Open `https://my-task-manager-api.herokuapp.com/users/me` with a GET Request

### Editing Profile as a User:

Open `https://my-task-manager-api.herokuapp.com/users/me` with a PATCH Request with the User Details as shown in the User Model enclosed in a JSON Object

### Deleting Profile as a User:

Open `https://my-task-manager-api.herokuapp.com/users/me` with a DELETE Request

### Uploading Profile Image as a User:

Open `https://my-task-manager-api.herokuapp.com/user/me/avatar` with a POST Request with the User Image as shown in the User Model enclosed in a JSON Object

### Deleting Profile Image as a User:

Open `https://my-task-manager-api.herokuapp.com/user/me/avatar` with a DELETE Request

## Task Routes

### Creating a Task:

Open `https://my-task-manager-api.herokuapp.com/tasks` with a POST Request with the Task Details as shown in the Task Model enclosed in a JSON Object

### Getting the Tasks:

Open `https://my-task-manager-api.herokuapp.com/tasks` with a GET Request

### Getting a specific Task:

Open `https://my-task-manager-api.herokuapp.com/tasks/{task._id}` with a GET Request

### Editing a Task:

Open `https://my-task-manager-api.herokuapp.com/tasks/{task._id}` with a PATCH Request with the Task Details as shown in the Task Model enclosed in a JSON Object

### Deleting a Task:

Open `https://my-task-manager-api.herokuapp.com/tasks/{task._id}` with a DELETE Request
