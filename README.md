# Minumum Viable ES6 NPM Package

## Why create minimum viable es6 npm package repo?
A minimum viable npm package is very simple -- just create a package.json with a name and a version in a folder and upload.

However, if you want to write in es6, then you probably want to still publish in es5.  This adds a little complexity.

This package has a few parts put in place to make that work.

1. The source files are placed in a source folder.
2. .babelrc and package.json are set up so that a build command will populate the build folder.
3. main is declared to be index.js in the build folder.
4. tests are in the tests folder
5. jest is added as a dev-dependancy and a test script is provided
6. .gitignore avoids committing the generated es5.
7. .npmignore avoids adding the source code.

## Cool.  So what do I do to use it?

It's pretty easy.  Here are the steps.

