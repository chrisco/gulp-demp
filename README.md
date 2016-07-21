# Gulp Demo

Based on Gulp Docs:    
https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md

## What I Did

#### 1. Install gulp globally:

__If you have previously installed a version of gulp globally, please run `npm rm --global gulp`
to make sure your old version doesn't collide with gulp-cli.__

```sh
$ npm install --global gulp-cli
```

#### 2. Initialize your project directory:

```sh
$ npm init
```

#### 3. Install gulp in your project devDependencies:

```sh
$ npm install --save-dev gulp
```

#### 4. Create a `gulpfile.js` at the root of your project:

```js
var gulp = require('gulp');

gulp.task('default', function() {
  // place code for your default task here
});
```

#### 5. Run gulp:

```sh
$ gulp
```

That worked.

#### Then Elana said to run this:

```
$ npm i gulp-sass -S
```

#### And edit the directories and files...

As per this repo.

Gulp watches my scss folder and run the styles task on changes, outputting to the build/css director.

Triggers the 'styles' task with this command:

```
$ gulp styles
```

Triggers the 'default' task, which is a 'watch,' in my case, with this command:

```
$ gulp
```

It works.

## More Info and Exercises

* [Galvanize Exercises](https://github.com/gSchool/gulp-exercises)
* [Danny's Slides](https://docs.google.com/presentation/d/1VahNgKsXsQOOtOXgS0HPeQd9blqrVPjbghOqJZ24XCQ/edit#slide=id.p)
* [Gulp's 'Getting Started' Docs on Github](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
