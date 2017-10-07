# broiler-plate-setup

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.16.0.

Requirements: 
1. install node js globally on your machine. follow the link https://nodejs.org/en/ and get download most recommended for users.
2. install ruby gems with compass and sass.(as we will use sass preprocessor for css).
3. follow the next steps one by one:
    -> npm install -g yo grunt-cli bower
    -> npm install -g generator-angular
    -> yo angular 
    
      after these commands the following folder structure is found in your project directory
      
      .bowerrc
      .editorconfig
      .gitattributes
      .gitignore
      .jshintrc
      Gruntfile.js
      app/
      component.json
      karma-e2e.conf.js
      karma.conf.js
      node_modules/
      package.json
      test/
  
      Next: The first thing we need to do is make a small change to our Bower config in .bowerrc so open it up and add the following line:
      
      {
          "directory": "app/components",
          "json": "bower.json" // Add this line
      }
    
    -> bower install angular-bootstrap --save

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.
