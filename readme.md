# Welcome to API Logic Server

You are currently in an empty project, pre-configured for the ApiLogicServer Docker container
(note the `.devcontainer` and `Dockerfile`).

&nbsp;

## Create

To create your project:
1. Open a terminal window
2. Enter the following command:

```
ApiLogicServer create --project_name=.  # include the period - it designates the current directory
```

You will then be asked to supply the `db_url`
* Press RETURN to use the sample project

The project will be created in your current directory (e.g, `working_software_now`).

### Using your own database
After you have explored the sample, try it with your own database by specifying an appropriate `db_url`.   For examples, enter the Terminal command: 
```
ApiLogicServer examples
```
&nbsp;

## Run
To run your project, use the created launch configurations to start the API or the Basic Web App.

> If you are using your own database, you will need to [configure the Web App](https://github.com/valhuber/ApiLogicServer/wiki/Working-with-Flask-AppBuilder).



&nbsp;&nbsp;
# Overview

ApiLogicServer creates database api projects:

* Created projects are instantly executable, providing a database API and a web app

* Customize the projects in an IDE such as VS Code

   * In particular, use VS Code to create logic using spreadsheet-like rules

* Created projects utilize Python from the container, eliminating the need to install Python

<figure><img src="https://github.com/valhuber/ApiLogicServer/blob/main/images/creates-and-runs.png?raw=true"></figure>
