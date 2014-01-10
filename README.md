# GitHub For Geodata

## Vision

This repo will contain information on City of Philadelphia publishing open geodata on GitHub.

## Why GitHub?

GitHub is an ideal platform for releasing geodata to the public because it:

* gives GIS units control of when and how their data is updated to the general public
* allows other GitHub users to ask questions and raise issues about the data - creating a dialog around it
* displays a history of changes to the data that gives consumers notifications on updates
* allows for collaboration between staff and outside stakeholders
* Renders [CSV files as tables](https://github.com/blog/1601-see-your-csvs) and [GeoJSON as embeddable web maps](https://help.github.com/articles/mapping-geojson-files-on-github)

## But How?

Here's a somewhat crude diagram of how it will work:

![Data Flow Diagram](https://github.com/CityOfPhiladelphia/github-for-geodata/blob/master/images/dataflow.jpeg)

City staff will export data from GeoDb2 using [ArcOpen](https://github.com/CityOfPhiladelphia/arc-open) and then use [GitHub for Windows](http://windows.github.com/) to upload it to the GitHub.com remote repo for their department. The open data portals [PASDA](http://www.pasda.psu.edu/) and [OpenDataPhilly](http://opendataphilly.org/) so that the public can download the data from either or GitHub itself and always have the most up-to-date data.

## About This Repo

This repo contains various Markdown pages of information regarding the City of Philadelphia's plan and best practices for releasing geodata on GitHub. View these pages to get a sense of how everything works.

## Contributing

This repository will act as a living document that can be edited and added to as needed. If you would like to see something changed, make the changes and [send a pull request](https://help.github.com/articles/using-pull-requests)!  

Additionally, the [the issues tab](https://github.com/CityOfPhiladelphia/github-for-geodata/issues) is a good place for discussions regarding this plan.



