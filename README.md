# Frontend factory

Custom Gulp recipe for frontend development

* Mustache
* Bootstrap 4 / jQuery 3.2.1
* SASS

## STRUCTURE

```
/
|- app/
|   |- css/
|      |- map/
|   |- fonts/
|   |- images/ 
|   |- js/ 
|   |- scss/
|   |- vendor/
|      |- css/
|      |- js/
|      |- fonts/
|
|   |- index.html
|   |- templates
|      |- partials/
|
|- dist/
|   |- css/
|   |- maps/
|   |- fonts/
|   |- images/ 
|   |- js/ 
|   |- vendor/
|   |  |- css
|   |  |- js
|   |  |- fonts
|   |
|   |- index.html
|
|- gulpfile.js
|- package.json
|- README.md

```

> run ```gulp``` > watcher mode

> run ```gulp build``` > fresh copy on dist folder

:construction: :octocat: