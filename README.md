# workstyle-NLP-analysis

This project explores the evolving dynamics of remote vs. office work environments using text mining and natural language processing (NLP). Leveraging the NewsAPI and BeautifulSoup, the notebook gathers and analyzes web content around key workstyle-related themes such as "Hybrid Jobs", "Flexible Work", and "Office Culture".

## Project Overview

We collected news articles using keyword-driven queries to study how different work environments are portrayed and discussed across media. Articles were tagged and categorized into topics (e.g., *Technology & Jobs*, *Work Trends*, *Work Culture*) and viewpoints (*Online Working*, *Office Working*) to support sentiment and thematic analysis.

## Technologies Used

- Python
- `requests` & `BeautifulSoup` – Web scraping and data extraction
- `pandas` – Data manipulation
- NewsAPI – Article source
- Jupyter Notebook – Development environment

## Features

- Automated news article scraping based on keywords related to remote and office work
- Labeling articles with contextual topic and viewpoint
- Organized structured dataset ready for further sentiment or classification analysis

- Label Taxonomy

| View Label       | Topic Label                                  |
|------------------|----------------------------------------------|
| Online Working   | Work Trends, Technology & Jobs, Work Culture, Economy |
| Office Working   | Work-Life Balance, Productivity, Corporate Culture     |

## How to Use

1. Set your NewsAPI key in the notebook.
2. Run the notebook to fetch and process articles.
3. Export or extend the dataset for sentiment analysis, topic modeling, or visualization.
