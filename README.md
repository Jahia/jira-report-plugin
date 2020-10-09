[![CircleCI](https://circleci.com/gh/rknj/release-notes-report-plugin/tree/master.svg?style=svg)](https://circleci.com/gh/rknj/release-notes-report-plugin/tree/master)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/rknj/release-notes-report-plugin)
![License](https://img.shields.io/badge/license-MIT-green)

# Jira Report for Release Notes

This report has been created to build a Release Notes with issues grouped by version and component.
Please note that this report is based on the custom field "Changelog Notes" but if you do not have it it will display the summary.

With the last version of the report you will have the following options available:

<img src="src/main/resources/images/report_config.png" alt="Report configuration" width="500"/>

## Installation

- Get the latest version of the add-on and deploy it on your Jira instance
- In the project report tab you’ll see a new entry **Release Notes By Version And Component** in the **Other** section

<img src="img/report-access.png" alt="Report configuration" width="500"/>

## Useful commands
- atlas-run: to run a local instance of Jira
- atlas-package: to build the add-on
- atlas-mvn: Maven command to use with Atlassian SDK (ex: for release:prepare and release:perform)

## Tutorial

This module has been created following the Atlassian tutorial: https://developer.atlassian.com/server/jira/platform/creating-a-jira-report/

## Useful links

- https://developer.atlassian.com/server/jira/platform/report/
- https://docs.atlassian.com/software/jira/docs/api/6.4.12/
- https://developer.atlassian.com/server/framework/atlassian-sdk/packaging-and-releasing-your-plugin/
- https://developer.atlassian.com/server/jira/platform/object-configurable-parameters/
