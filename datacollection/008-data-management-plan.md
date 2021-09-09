# Data management plan

A list of high level goals:
- Collect data
- Transform data into a specific standard
- Store data
- Retrieve data and feed it into a data analytics tool

## Collect data

We identified ODK as one of the data collection tooling options. Data is collected via custom forms created on [ODK Build](https://build.getodk.org).


## Transform data

One option is to use OData, the standard that ODK supports by default to directly interact with the data using tools like Excel/Power BI, R, Tableau etc.

Data collected via ODK can also be transformed into frictionless data through [Frictionless Framework](https://framework.frictionlessdata.io).


## Store Data

The data collected from ODK Central can be routed to a DB (like Postgres) and be saved there.


## Retrieve and analyze data

The data can be retrieved from the DB and can be fed into exploratory data analysis tools like Apache Superset, Metabase, etc.

