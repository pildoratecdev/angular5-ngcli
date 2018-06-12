# tecDev.es - Visual Studio NPM Task Runner 
Here you can find the steps you need to follow the [YouTube video](https://www.youtube.com/watch?v=tNxlWQdhltQ):

1. Download [this repository](https://github.com/tecdevcode/angular5-ngcli) from GitHub.

2. Open the project in Visual Studio 2017.

3. Install Grunt CLI at machine level (if not installed yet) using this command: `npm install grunt-cli -g`

4. Install Grunt from the command line at project level (executing the command in the root directory of the downloaded repository). To install Grunt use this command: `npm install grunt --save-dev`

5. Get the code at the [Sample Gruntfile page](https://gruntjs.com/sample-gruntfile) and copy it to a new file in the project root named [Gruntfile.js](https://github.com/tecdevcode/angular5-ngcli/blob/gulp-grunt/Gruntfile.js).

6. Install Gulp CLI at machine level (if not installed yet) using this command: `npm install gulp-cli -g`

7. Install Gulp from the command line at project level (executing the command in the root directory of the downloaded repository). To install Gulp use this command: `npm install gulp --save-dev`

8. Create a [Gulpfile.js](https://github.com/tecdevcode/angular5-ngcli/blob/gulp-grunt/gulpfile.js) file using this command at project root: `touch gulpfile.js`

9. Copy the code for gulpfile.js from the bottom of the [Gulp official site](https://gulpjs.com) and paste it in the Gulpfile.js file created in the last step. Delete all tasks but default, [as shown in our repository](https://github.com/tecdevcode/angular5-ngcli/blob/gulp-grunt/gulpfile.js).

10. Install the [NPM Task Runner extension](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.NPMTaskRunner) from Visual Studio 2017 (Tools > Extensions and updates > Online) and restart Visual Studio.