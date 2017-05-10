# minimum viable es6 npm package
A minmimal npm package can be very small -- just create a package.json with a name and a version.

However, is you want to write in es6, then you probably want to still publish in es5.

This package has a few parts to make that work.

1. The source files are placed in a source folder.
2. .babelrc and package.json are set up so that a build command will populate the build folder.
3. main is declared to be index.js in the build folder.
4. tests are in the tests folder
5. jest is added as a dev-dependancy and a test script is provided
6. .gitignore avoids committing the generated es5.
7. .npmignore avoids adding the source code.

