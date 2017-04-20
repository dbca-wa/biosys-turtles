# biosys-turtles
Requirements for Biosys milestone "Turtles".

We will have to author, maintain and work on these requirements for a long time, and in a distributed, online manner.
Therefore, this repository is an attempt to bring light and order into the murky kelp forest of requirements.

## Workflow

* The [WAStD documentation](http://wastd.readthedocs.io/business_analysts.html) contains a nice write-up of the status quo, and
  a good few business requirements. We want to extract and formalise them.
* The `ISSUE_TEMPLATE` contains the formalised structure for the issue's narrative together with usage instructions.
* Contributors raise issues [here](https://github.com/parksandwildlife/biosys-turtles/issues) and follow instructions.
* Issues will automatically pop up on the [Kanban board](https://waffle.io/parksandwildlife/biosys-turtles), where logged in
  contributors can re-arrange isses to sort them by priority. Kanban lanes are named (and apply labels) after priorities.
* Any outputs will be created by RMarkdown workbooks or R Shiny apps, consuming the issues through the GitHub API, and formatting
  them according to the respectively required output format. This will allow us to generate multiple outputs from one cnetrally
  maintained set of issues. The workbooks and apps will be kept under version control in this repository, and the hosted versions
  will be linked in this README.
  
## Inputs

* [WAStD documentation](http://wastd.readthedocs.io/business_analysts.html) to find requirements
* [GitHub Issues](https://github.com/parksandwildlife/biosys-turtles/issues) to create issues from requirements
* [Kanban board](https://waffle.io/parksandwildlife/biosys-turtles) to update, sort and re-prioritise requirements

## Outputs

* [Requirements spreadsheets for OIM](https://yes-we-ckan.shinyapps.io/BiosysTurtlesRequirements/) ([source](https://github.com/parksandwildlife/turtle-scripts/tree/master/requirements/BiosysTurtlesRequirements)) - rough as guts proof-of-concept but work in progress
