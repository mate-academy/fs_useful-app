# Useful App

Create an application (both backend and frontend) to manage a list of items. You can choose any kind of items as long as keeping track of them is useful to you: that can be movies you are planning to watch, books you have recently read, ideas you come up with, etc.

You should implement authentication by means of sessions and a database table listing all the users and their password hashes. Each item in your main table must be associated with one of the users (the one who created it), so each user of your app will be managing his individual list of items.

Each authenticated user must be able to add a new item, edit or remove an existing item, and view all the items that he has already created. You should also provide a capability of signing out.

Handle all possible kinds of errors gracefully (for instance, return 401 when the user is not authorized for an action and present the user an opportunity to reenter his credentials if the server responds with 401).

You are encouraged to use [Semantic UI React](https://react.semantic-ui.com/) or another CSS framework in order to make your project look prettier. Try to create as friendly a user interface as possible. Show a [loader](https://react.semantic-ui.com/elements/loader/) when necessary.

Also, please include SQL used to create your DB tables here:

```postgresql
... SQL ...
```
