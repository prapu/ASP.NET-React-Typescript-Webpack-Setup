# ASP.NET-React-Typescript-Webpack-Setup
How to setup reactjs typescript webpack in ASP.NET MVC project
How to use this project?
Clone the project into a local folder. Open the ASP.NET solution and restore all the packages by right clicking packages.config file. Process will take a minute or two.
Next step restore node packages. You can use either VS20127 command line or you can open windows command prompt and go to your project folder and type following node command
npm i
This command will restore all the package dependancies required to run ASP.NET solution.
Next open up the task runner window and run webpack dev task. It will compile the typescript files and create a minified bundle
Now compile and run the ASP.NET solution you will see React initial setup screen.
