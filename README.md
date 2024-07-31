# Batch Twitter Sentiment Analysis

This project performs sentiment analysis on Twitter data in a batch processing manner using the `ntscraper` library, Hadoop clusters (HDFS), and PySpark.

## Overview

Twitter is a valuable source of data for sentiment analysis. This project focuses on analyzing tweets in batches rather than real-time, making it suitable for processing large volumes of historical Twitter data. The sentiment analysis is performed using PySpark, a Python library for parallel computing with Spark, leveraging Hadoop clusters for distributed computing.

## Features

- **ntscraper Library**: Utilizes the `ntscraper` library to scrape tweets based on specified criteria such as keywords, hashtags, or user handles.
- **Hadoop Clusters (HDFS)**: Stores the scraped Twitter data in Hadoop Distributed File System (HDFS), enabling distributed storage and processing.
- **PySpark**: Processes the Twitter data stored in HDFS using PySpark.

<a href="https://ibb.co/NyrbXkJ"><img src="https://i.ibb.co/FDXC9fy/image.png" alt="image" border="0"></a>

## Requirements

- Python 3.x
- ntscraper Library
- Hadoop Cluster (for HDFS storage and distributed processing)
- PySpark

## Setup

1. **ntscraper Library Installation**: Install the `ntscraper` library using `pip`:

```bash
pip install ntscraper
```

2. **Hadoop Cluster Configuration**: Set up a Hadoop cluster and configure HDFS. Ensure that the necessary permissions are granted for accessing and writing data to HDFS.

3. **PySpark Installation**: PySpark comes pre-installed with Apache Spark. You can install Apache Spark locally or use a cloud-based Spark service.

## Usage

1. **Scrape Tweets**: Use the `ntscraper` library to scrape tweets based on your criteria (keywords, hashtags, user handles).

2. **Store Data in HDFS**: Transfer the scraped Twitter data to HDFS for distributed storage.

3. **Perform Sentiment Analysis**: Execute the PySpark script `sentiment_analysis.py` to analyze the sentiment of the Twitter data stored in HDFS.

```bash
python sentiment_analysis.py (use ipynb)
```

## Contributors

- Ahmed Abdullah
- Ibtehaj Ali
- Maira

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
