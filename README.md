# PARSE — Pakistan Automated Risk and Security Engine

**An AI-powered platform for security intelligence monitoring, incident extraction, and early-warning analysis in Pakistan.**

## Overview

PARSE collects and analyzes publicly available information from Pakistani news sources, social media, government announcements, and economic data feeds. It uses AI, Natural Language Processing (NLP), and anomaly detection to identify security incidents, track entities, detect patterns, and generate alerts for human analysts.

## Key Features

- **Multi-Source Data Ingestion:** Collect data from news websites, social media, government sources, and economic feeds.
- **AI Information Extraction:** Extract structured incident information using Google Gemini.
- **Multilingual NER:** Identify people, organizations, and locations in English, Urdu, and Roman Urdu.
- **Entity Resolution:** Match aliases and alternative names across sources.
- **Entity Profiling:** Track historical mentions and reporting patterns.
- **Anomaly Detection:** Identify activity spikes, narrative shifts, and unusual reporting patterns.
- **Early-Warning Alerts:** Generate alerts for analyst review.
- **Interactive Dashboard:** Visualize incidents using maps, charts, and reports.

## Technology Stack

- **Backend:** Python, FastAPI
- **Data Collection:** Scrapy, BeautifulSoup, REST APIs
- **Task Queue:** Celery, Redis
- **AI/NLP:** Google Gemini API, Multilingual BERT, spaCy
- **Database:** PostgreSQL
- **Frontend:** React.js
- **Visualization:** MapLibre GL JS, Recharts
- **DevOps & Testing:** Docker, GitHub Actions, Pytest

## System Workflow

1. Collect data from multiple sources.
2. Clean text, detect language, and remove duplicates.
3. Extract incidents and entities using AI and NLP.
4. Resolve entity aliases and build profiles.
5. Detect anomalies and generate alerts.
6. Display results on the analyst dashboard.

## Project Objectives

- Automate information collection and processing.
- Reduce manual analysis time.
- Identify patterns across multiple sources.
- Support verification through source references and human review.
- Evaluate extraction accuracy and early-warning performance.

## Installation

Installation instructions will be added as the backend and frontend implementation progresses.

## Project Status

**In Development** — Building the data ingestion pipeline, AI extraction engine, entity resolution system, anomaly detection module, and dashboard.

## Responsible Use

PARSE is designed to support human analysis. Automated extractions and alerts are not proof of an incident, and information should be verified against reliable sources before conclusions are drawn.

## License

To be determined.
