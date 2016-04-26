# AngularSPA

Single page app with angular ([from sctoch.io tutorial](https://scotch.io/tutorials/creating-a-single-page-todo-app-with-node-and-angular))

After cloning the repo to your local you can run the app by;

First, installing the modules in package.json:

``` npm install ```

Second, running the server:

``` node server.js ```

*Following the full tutorial will end up in a failing app. That's why you should change the route from 
```
app.get('*', function(req, res) {
        res.sendfile('./public/index.html');
    });
```
to
```
app.get('', function(req, res) {
        res.sendfile('./public/index.html');
    });
```
