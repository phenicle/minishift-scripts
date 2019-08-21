# minishift-scripts
Scripts that make it possible to create (build and deploy) and remove apps with a single command.

This provides two scripts: mcp-mk-app and mcp-rm-app.

mcp-mk-app   
Minishift Make App

 USAGE

  mcp-mk-app <app-name> <scm-url>

 where

   <app-name> is the name used to identify the app, and
   <scm-url>  is the URL of the application in SCM.

  The value of <app-name> must match the SCM repository name, i.e. the last part of <scm-url>, sans extension.
  This script assumes your project is named 'myproject'.

TODO: parametrize the minishift project name.


mcp-rm-app
Minishift Remove App

 USAGE

  mcp-rm-app <app-name>

 where <app-name> is the name used to identify the app.
