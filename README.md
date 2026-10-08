# Visual Studio code base Modeler of Salesforce CGCloud mobile app

This tool is used to customize the Salesforce CGCloud mobile app for client needs.
Use this README to document the details of your project and related information. The format and structure provided in this file are purely for reference, feel free to modify as needed.

## Description

TODO: An in-depth paragraph about your project and overview of use.

## Getting Started

### Dependencies

* Node
* Visual Studio code
* Python
* Salesforce DX

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
see [@document](https://docs.google.com/document/d/17NSPTXFnglzkDhOixF5qUaRwRiuY2woeT3DmM6coxC0/edit#heading=h.s9auy9z21lwm)
```

## Folder structure explanation

### appl

* contains the build results (build folder), downloaded data during test (data folder) and a config section for the simulation of the app (config folder)

### src

* contains the source code and contracts of your salesforce mobile app

### templates

* snippets for new contracts to improve customizer efficiency

### test

* (preparation for the future) location for your unit test of the corresponding source section

## Help

### Helpful commands
Check sf plugins:
* sf plugins


Install modeler cli plugin:
* sf plugins install @ind-rcg/modeler-sfdx-cli-plugin

To create a Workspace:
* sf modeler workspace create

To generate the runtime artefacts:
* sf modeler workspace build (alias: sf mdl build)

To start the local application server:
* sf modeler workspace server start (alias: sf mdl simulate)

Generate the deployment Package:
* sf modeler workspace package (sf mdl package)

Kill the process running on port 3000:
```
MAC: kill -9 $(lsof -ti:3000)
Windows:
netstat -ano | findstr :3000
Use process id in <PID> in the next statement
taskkill /PID <PID> /F
```


Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. [@Salesforce](https://salesforce.com)

## Version History

* 1.0
    * Basic version
* 0.1
    * Initial Release

## License

TODO: This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [TODO]
