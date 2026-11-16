# Belly Button Biodiversity Dashboard

## Project Overview

This project develops an interactive data visualization dashboard to explore microbial biodiversity data collected from human belly button samples.

The dashboard allows users to select individual test subjects and examine their microbial sample information through interactive charts and demographic summaries.

The project demonstrates the use of JavaScript, D3.js, and Plotly.js to transform structured biological data into an accessible, interactive analytical interface.

## Project Objectives

- Develop an interactive dashboard for exploring microbial biodiversity.
- Visualize the most abundant operational taxonomic units (OTUs) for individual subjects.
- Display demographic information associated with each subject.
- Compare microbial sample distributions using interactive visualizations.
- Demonstrate dynamic data filtering and chart updates using JavaScript.

## Dataset

The project uses a JSON dataset containing microbial sample measurements and demographic information.

The dataset includes:

- Test subject identifiers
- Demographic characteristics
- Operational taxonomic unit (OTU) identifiers
- Microbial sample values
- OTU descriptions
- Belly button washing frequency

The repository includes a copy of the dataset named `samples.json`.

The current JavaScript implementation retrieves the dataset from an external educational data source.

## Technologies Used

- JavaScript
- HTML5
- Bootstrap
- D3.js
- Plotly.js
- JSON
- GitHub

## Dashboard Features

### 1. Subject Selection

An interactive dropdown menu allows users to select a test subject. Selecting a different subject updates the dashboard's visualizations and demographic information.

### 2. Demographic Information

A demographic panel displays available information associated with the selected subject.

### 3. Horizontal Bar Chart

A horizontal bar chart displays the ten most abundant OTUs for the selected subject.

### 4. Bubble Chart

An interactive bubble chart visualizes microbial sample values and OTU identifiers.

### 5. Washing Frequency Gauge

A gauge chart displays the selected subject's recorded belly button washing frequency.

## Repository Structure

```text
belly-button-challenge/
├── index.html
├── samples.json
├── static/
│   └── js/
│       └── app.js
├── README.md
└── .gitignore
```

## How to Run the Dashboard

1. Download or clone the repository.
2. Open a terminal in the repository's root directory.
3. Start a local web server using Python:

   `python -m http.server 8000`

4. Open `http://localhost:8000` in your browser.
5. Select a test subject from the dropdown menu to explore the dashboard.

An internet connection is required for the external JavaScript libraries and the dataset URL used by the current implementation.

## Analytical Value

This project demonstrates interactive data exploration, dynamic filtering, JSON data processing, and JavaScript-based visualization.

The dashboard provides a practical example of presenting multidimensional scientific data through an interactive interface.

## Limitations

- The dashboard is designed for exploratory analysis rather than clinical interpretation.
- The current application depends on an external dataset URL.
- The dashboard's functionality depends on the availability of its JavaScript libraries and data source.
- The project does not perform predictive modeling or statistical hypothesis testing.

## Acknowledgments

Development assistance was provided through AskBCS, including support from Robert Perron and Sunshine.

## Author

Adam A. Saenz

Data Science Portfolio: https://adamsaenz.github.io/
