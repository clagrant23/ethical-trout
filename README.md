# Ethical Trout

Ethical Trout is a conservation-focused data science project that uses live USGS river data to help anglers evaluate current trout fishing conditions in Western North Carolina.

The project retrieves water temperature, streamflow, and gage height data from USGS monitoring stations and applies transparent decision rules to provide a fishing status, explanation, and conservation-oriented guidance.

## Motivation

Trout are cold-water fish that can experience increased stress during warm water and abnormal stream conditions. This project was created to explore how publicly available environmental data can be turned into a practical tool for anglers interested in making more informed and responsible fishing decisions.

## Current Features

- Retrieves live river data from the USGS API
- Processes JSON responses using Python
- Analyzes multiple Western North Carolina rivers
- Tracks water temperature, streamflow, and gage height
- Compares current streamflow with recent conditions
- Generates a fishing status, reason, and guidance for each river
- Produces human-readable river reports

## Current Rivers

The project currently includes monitoring stations for several Western North Carolina rivers and trout streams, including:

- Davidson River
- Mills River
- Cataloochee Creek
- Oconaluftee River
- French Broad River

## Project Status

The data collection and recommendation backend is currently functional.

The next stage of development is to build a simple web application that allows users to select a river and view current conditions and conservation guidance.

## Planned Development

- Build a Streamlit web interface
- Improve handling of missing or stale USGS observations
- Display data timestamps and sources
- Add river condition visualizations
- Review and document the scientific basis for recommendation thresholds
- Improve streamflow comparisons using historical seasonal data
- Gather feedback from local fishing and conservation stakeholders
- Deploy a public pilot

## Data Source

River conditions are retrieved from the U.S. Geological Survey (USGS) Water Services.
