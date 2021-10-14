# API Logic Server


<figure><img src="https://github.com/valhuber/ApiLogicServer/blob/main/images/creates-and-runs.png?raw=true"></figure>


Welcome to ApiLogicServer.

This is an empty project, pre-configure for the ApiLogicServer Docker container.

To create your project, open a terminal window:
```
ApiLogicServer create project-name=.  # include the period - it designates the current directory
```

You will be asked to supply the `db_url`.
* Press RETURN to use the sample project (a pre-installed database), or
* Provide your own db_url (for examples, try `ApiLogicServer examples`)

The project will be created in your current directory.

Use the created launch configurations to start the API or the Basic Web App.

> If you are using your own database, you will need to [configure the Web App](https://github.com/valhuber/ApiLogicServer/wiki/Working-with-Flask-AppBuilder).


