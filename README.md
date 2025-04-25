# 🏏 T20 Ontology-Based Analysis

This project explores **ontology-based knowledge representation and reasoning (KRR)** for analyzing **T20 cricket match data**. It uses semantic web technologies to build a structured, queryable, and inferable knowledge base from T20 match statistics.

## 📌 Project Overview

The notebook demonstrates:
- Construction of a **T20 Cricket Ontology**.
- Parsing and integrating real match data from CSV files into RDF format.
- Performing **semantic queries using SPARQL**.
- Using RDF reasoning to infer relationships and player/team insights.
- Leveraging `rdflib` in Python to process and manipulate RDF graphs.

## 📁 Files

- `KRR Project T20 Ontology Based Analysis.ipynb` — Main notebook for ontology creation, data ingestion, and semantic querying.
- `1st Innings T20.csv` — Raw CSV data from the first innings of a T20 match.
- `2nd Innings T20.csv` — Raw CSV data from the second innings of the same match.
- `latest_data.rdf` — Serialized RDF graph built from the innings data and ontology.

## 🛠️ Technologies Used

- Python 3.x
- [rdflib](https://rdflib.readthedocs.io/en/stable/) — RDF manipulation and SPARQL querying
- RDF, RDFS, OWL — for ontology modeling
- SPARQL — for querying semantic data
- Jupyter Notebook — interactive development and demonstration

## ⚙️ Features

- 🧱 Ontology design for cricket matches including players, teams, and performance data.
- 🧬 Conversion of CSV statistics into RDF triples.
- 🔍 Semantic querying over the RDF graph using SPARQL.
- 🧠 Reasoning over structured knowledge to infer team strengths, key performers, etc.

## 🧠 Ontology Highlights

- **Classes**: `Player`, `Team`, `Innings`, `Match`, `Performance`
- **Properties**:
  - `hasPlayer`, `belongsToTeam`, `scoredRuns`, `tookWicket`, `playedInInnings`
- **Data integration**: CSV to RDF graph

## 📦 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/t20-ontology-analysis.git
   cd t20-ontology-analysis
