# Donor Network Visualizer

This module generates interactive network visualizations of campaign finance donor networks for Sacramento. It creates an HTML visualization that shows connections between donors and campaigns.

## Prerequisites

- Python 3.7 or higher

## Setup

### 0. Navigate to the Visualizer Directory

Make sure you're in the `visualizer` folder before proceeding:

```bash
cd visualizer
```

### 1. Install Python

Ensure you have Python 3.7+ installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

To verify your Python installation:
```bash
python --version
```

### 2. Create a Virtual Environment

It's recommended to use a virtual environment to isolate project dependencies. Create and activate one:

```bash
python -m venv venv
```

Activate the virtual environment:

**On macOS/Linux:**
```bash
source venv/bin/activate
```

**On Windows:**
```bash
venv\Scripts\activate
```

### 3. Install Dependencies

Install the required Python packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

This will install:
- **jupyter** - Interactive notebook environment
- **networkx** - Network analysis and graph algorithms
- **pandas** - Data manipulation and analysis
- **pyvis** - Interactive network visualizations
- **matplotlib** - Data visualization
- **scipy** - Scientific computing

## Running the Visualizer

### Execute the Notebook

Run the Jupyter notebook to generate the donor network visualization:

```bash
jupyter notebook donor_network_visualizer.ipynb
```

This will open a Jupyter notebook interface in your browser. Execute the cells in the notebook to:
1. Load campaign finance data
2. Process and analyze donor networks
3. Generate the network visualization
4. Export the visualization as an HTML file

### Output

The notebook will generate an **HTML file** containing an interactive network visualization. This file can be opened in any web browser to explore:
- Nodes representing donors and campaigns
- Edges showing donation connections
- Network statistics and relationships

## Notes

- Ensure you have the campaign finance data files in the appropriate location before running the notebook
- The HTML output can be shared and viewed without requiring Python or Jupyter installed
- Network visualizations are interactive - you can zoom, pan, and hover over nodes to explore details
