# angular-seed-lite

This project is an application skeleton for a typical [AngularJS](http://angularjs.org/) web app.
It is an even lighter version of [angular-seed] (https://github.com/angular/angular-seed).

## Getting Started

```
git clone https://github.com/chadeddington/angular-seed-lite
cd angular-seed
```

If you just want to start a new project without the angular-seed commit history then you can do:

```bash
git clone --depth=1 https://github.com/chadeddington/angular-seed-lite <your-project-name>
```

The `depth=1` tells git to only pull down one commit worth of historical data.


```
npm install
```

Behind the scenes this will also call `bower install`.  You should find that you have two new
folders in your project.

* `node_modules` - contains the npm packages for the tools we need
* `app/bower_components` - contains the angular framework files

*Note that the `bower_components` folder would normally be installed in the root folder but
angular-seed changes this location through the `.bowerrc` file.  Putting it in the app folder makes
it easier to serve the files by a webserver.*

### Run the Application

We have preconfigured the project with a simple development web server.  The simplest way to start
this server is:

```
npm start
```

Now browse to the app at `http://localhost:8000/app/index.html`.



## Directory Layout

```
app/                    --> all of the source files for the application
  view1/                --> the view1 view template and logic
    view1.html            --> the partial template
    view1.js              --> the controller logic
  view2/                --> the view2 view template and logic
    view2.html            --> the partial template
    view2.js              --> the controller logic
  app.css               --> default stylesheet
  app.js                --> main application module
  index.html            --> app layout file (the main html template file of the app)
```