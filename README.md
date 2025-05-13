# Reddit Data Pipeline with Airflow and Docker

A data engineering pipeline that extracts, transforms, and loads Reddit data using Apache Airflow, orchestrated in Docker containers.

## Features

- **Reddit API Integration**: Extract posts and comments using PRAW
- **Data Processing**: Clean and transform Reddit data
- **Airflow Orchestration**: Scheduled workflows with dependency management
- **Dockerized Environment**: Reproducible containerized setup
- **CSV Output**: Store processed data in partitioned files

## Prerequisites

- Docker Engine (v20.10+)
- Docker Compose (v1.29+)
- Reddit API credentials (create at [Reddit Apps](https://www.reddit.com/prefs/apps))

## Project Structure
