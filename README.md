# Angular-Login-and-Registration-form
Running the Angular 10 Login Tutorial Example Locally
Install NodeJS and NPM from https://nodejs.org.
Download or clone the Angular project source code from https://github.com/cornflourblue/angular-10-registration-login-example
Install all required npm packages by running npm install or npm i from the command line in the project root folder (where the package.json is located).
Start the app by running npm start from the command line in the project root folder, this will compile the Angular app and automatically launch it in the browser on the URL http://localhost:4200.
NOTE: You can also start the app with the Angular CLI command ng serve --open. To do this first install the Angular CLI globally on your system with the command npm install -g @angular/cli.

For more info on setting up an Angular development environment see Angular - Setup Development Environment.


Running the Angular App with an ASP.NET Core 3.1 API
For full details about the example ASP.NET Core API see the post ASP.NET Core 3.1 - Simple API for Authentication, Registration and User Management. But to get up and running quickly just follow the below steps.

Install the .NET Core SDK from https://www.microsoft.com/net/download/core.
Download or clone the project source code from https://github.com/cornflourblue/aspnet-core-3-registration-login-api
Start the api by running dotnet run from the command line in the project root folder (where the WebApi.csproj file is located), you should see the message Now listening on: http://localhost:4000.
Back in the Angular app, remove or comment out the line below the comment // provider used to create fake backend located in the /src/app/app.module.ts file, then start the Angular app and it should now be hooked up with the ASP.NET Core API.

Running the Angular App with a Node.js + MySQL API
For full details about the example Node.js + MySQL API see the post NodeJS + MySQL - Simple API for Authentication, Registration and User Management. But to get up and running quickly just follow the below steps.

Install MySQL Community Server from https://dev.mysql.com/downloads/mysql/ and ensure it is started. Installation instructions are available at https://dev.mysql.com/doc/refman/8.0/en/installing.html.
Download or clone the project source code from https://github.com/cornflourblue/node-mysql-registration-login-api
Install all required npm packages by running npm install or npm i from the command line in the project root folder (where the package.json is located).
Start the api by running npm start from the command line in the project root folder, you should see the message Server listening on port 4000.
Back in the Angular app, remove or comment out the line below the comment // provider used to create fake backend located in the /src/app/app.module.ts file, then start the Angular app and it should now be hooked up with the Node + MySQL API.
