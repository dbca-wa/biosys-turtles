# biosys-turtles
This repository maintains the outputs of a requirements analysis for the Biosys milestone "Turtles".

We will have to author, maintain and work on these requirements for a long time in a distributed yet accessible manner.
Therefore, this repository is an attempt to bring light and order into the murky kelp forest of requirements.

We combine Sphinx documentation, GitHub issues, Kanban boards, and R Shiny apps to apply a DRY paradigm on the traditionally spreadsheet-driven project management aspect - everyone gets the contribution pathways and output formats they need, and yet we manage the information in one place.

## Workflow

* The [WAStD documentation](http://wastd.readthedocs.io/business_analysts.html) contains 
  an exhaustive write-up of the status quo, and a good few business requirements. 
  We want to extract and formalise them.
* The `ISSUE_TEMPLATE` contains the formalised structure for the issue's narrative 
  together with usage instructions.
* Contributors raise issues [here](https://github.com/parksandwildlife/biosys-turtles/issues)
  and follow instructions.
* Issues will automatically pop up on the 
  [![Kanban board](https://badge.waffle.io/parksandwildlife/biosys-turtles.svg?label=must-have&title=KanbanBoard)](http://waffle.io/parksandwildlife/biosys-turtles), where logged in
  contributors can re-arrange isses to sort them by priority:
  Kanban lanes are named (and apply labels) after priorities.
* Any outputs will be created by RMarkdown workbooks or R Shiny apps, consuming the issues 
  through the GitHub API, and formatting them according to the respectively required output format. 
  This will allow us to generate multiple outputs from one centrally maintained set of issues. 
  The workbooks and apps will be kept under version control, and the hosted versions will be linked here.
  
## Inputs

* Read [WAStD documentation](http://wastd.readthedocs.io/business_analysts.html) to find requirements
* Use [GitHub Issues](https://github.com/parksandwildlife/biosys-turtles/issues) to create issues from requirements
* View [Kanban board](https://waffle.io/parksandwildlife/biosys-turtles) to update, sort and re-prioritise requirements

## Outputs

* [Explore Requirements](https://yes-we-ckan.shinyapps.io/BiosysTurtlesRequirements/) ([source](https://github.com/parksandwildlife/turtle-scripts/tree/master/requirements/BiosysTurtlesRequirements)) - explore and export requirements
* Once the stakeholder consultation and write-up process is complete, we will produce a static document containing all outputs, and link it from here.
