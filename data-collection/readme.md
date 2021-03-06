# Data Collection

This folder contains details related to implementing the data collection feature.

### Challenges:

- The current way of collecting data is inefficient due to being mostly paper based, you have to manually email all the relevant stakeholders
- No standardization of availability and use
- No clear way of utilizing the data sitting in the source
- Need to analyze, annotate data to derive the necessary information out of it
- Problems related to the collection system that include but not limited to double entry, incorrect data etc.

### Requirements:

- Single system to collect data
- Collecting data on multiple factors including [both quantitative and qualitative](./004-data-categories.md)
- Ability to build forms that allow flexibility
- Periodically update existing data and collect new data
- Store the collected data for further analysis

### Methodology for identifying the tools

Read more about how we identified the tools listed the following section.
[Data collection tools and standards](./005-data-standards-and-tools.md)

### Tools identified

1. OpenDataKit(ODK)
2. KoboToolbox

We self-hosted OpenDataKit and it can be accessed via this URL: https://noralodk.civicdays.in

#### Guide on how to use ODK:

Here you can find the instructions on how to use ODK that is currently live:
[How to use ODK](https://github.com/The-Data-for-Children-Collaborative/noral-tech-research/blob/main/datacollection/006-odk.md#how-to-work-with-odk)


### Data management plan

Our high level goals for managing data are:
1. Collect data
2. Transform data into a specific standard
3. Store data
4. Retrieve data and feed it into data analytics tools to do information mapping, exploratory analysis, create dashboards etc.