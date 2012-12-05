# Can-Compile TodoMVC example

This folder mainly contains the [TodoMVC](http://todomvc.com) example for
[CanJS](http://todomvc.com/labs/architecture-examples/canjs/) and a Mustache and EJS CanJS view
in `development.html`.

`production.html` loads the `production/` build which contains all compiled views (in `production/views.production.js`)
and concatenated and minified files as generated by the Grunt file (see `grunt.js`).
You will notice that the production version won't make any requests to external view files and performs about
20% faster.