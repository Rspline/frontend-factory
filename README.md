# Frontend factory

Custom Gulp recipe for frontend development

* Mustache
* Bootstrap / jQuery
* SASS

## package.json
```
{
  "name": "frontend-factory",
  "version": "1.0.0",
  "description": "Mustache + Bootstrap + SASS + jQuery",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "sergioelmoreno.com",
  "license": "ISC",
  "devDependencies": {
    "browser-sync": "^2.18.8",
    "del": "^2.2.2",
    "gulp": "^3.9.1",
    "gulp-cache": "^0.4.6",
    "gulp-cssnano": "^2.1.2",
    "gulp-data": "^1.2.1",
    "gulp-if": "^2.0.2",
    "gulp-imagemin": "^3.2.0",
    "gulp-mustache": "^2.3.0",
    "gulp-sass": "^3.1.0",
    "gulp-uglify": "^2.1.2",
    "gulp-useref": "^3.1.2",
    "run-sequence": "^1.2.2"
  }
}


```

> run ```gulp``` > watcher mode

> run ```gulp build``` > fresh copy on dist folder

:construction: :octocat: