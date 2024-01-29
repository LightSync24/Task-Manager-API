1. connect.js is used to connect to the mongoDB database.
2. tasks.js inside the controllers folder has all the controllers, i.e., the methods for performing CRUD operations on the tasks.
3. for performing the update and delete operations, the user._id is also passed as URL parameter for identifying the task to be modified or delete.
4. tasks.js in the routes is for routing the user to desired link based on the operation they wish to perform.
5. Models folder has the mongoDB schema defined which will be used for storing the tasks.
