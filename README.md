# Tumbling_Window_Trigger_Demo
The Tumbling Window Trigger Demo demonstrates how to use a tumbling window trigger to schedule and manage periodic data processing tasks at fixed intervals, ensuring consistent data ingestion and processing over time

## Overview

In this demo, we implement a tumbling window trigger in Azure Data Factory (ADF) to automate data loading at defined intervals. This trigger helps manage data loads by creating fixed time windows, ensuring each data slice is processed only once. Tumbling windows can be used for periodic ingestion, incremental loads, and time-based aggregations.

## Features

- **Time-Based Data Ingestion**: Schedule data loads at fixed intervals without overlap.
- **Incremental Data Loads**: Efficiently load data for specific time windows to handle large datasets.


## Prerequisites

- **Azure Data Factory**: To create pipelines and configure triggers.
- **Azure Data Lake**: Storage for destination data.
- **SQL SERVER**: Storage for source data

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/BaddireddyManikantha/Tumbling_Window_Trigger_Demo.git
