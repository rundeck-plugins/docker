# docker-container

Three providers in this plugin:

* ResourceModelSource: Lists the containers as nodes
* NodeExecutor: Execute a command in a container via Command step or Commands page.
* WorkflowNodeSteps:
  * exec
  * inspect  
  * kill
  * pause
  * unpause
  * stats

## To build and install

Run the following commands to install the plugins:

    zip -r docker-container.zip docker-container
    cp docker-container.zip $RDECK_BASE/libext
