# Wikipedia Computer Science Network Analysis

This Python script builds a directed graph from Wikipedia articles related to "Computer Science" by recursively fetching links to other articles. It then analyzes the graph using PageRank to identify the most important articles in the network and provides a visualization of the graph.

## Features
- **Recursive Wikipedia Scraping**: Fetches links from Wikipedia articles related to Computer Science.
- **Graph Analysis**: Uses PageRank to rank the importance of articles.
- **Visualization**: Visualizes the network graph, highlighting the top-ranked articles.

## Requirements
- Python 3.x
- Required Libraries:
  - `requests`
  - `networkx`
  - `matplotlib`

Install the necessary packages using the following command:

```bash
pip install requests networkx matplotlib
