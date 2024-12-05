# Hadoop Installation and Word Count MapReduce on Google Colab

This repository demonstrates how to install Apache Hadoop on Google Colab and perform a MapReduce job to count the frequency of words in a text file.

## Features

- Install and configure Hadoop on Google Colab.
- Run a Word Count MapReduce example to process text data.

## Getting Started

### Installation Steps

1. **Clone this repository:**
   ```bash
   git clone https://github.com/ahfay/Hands-On-Hadoop-on-Google-Colab.git
   cd Hands-On-Hadoop-on-Google-Colab
   ```
2. Upload the **Hadoop_Hands_On.ipynb** file to Google Colab
3. Follow the Notebook Instructions:
   - Install Java and Hadoop
   - Adding Required Property to core-site.xml file
   - Formatting the HDFS File System
   - Monitoring Hadoop cluster with hadoop admin commands

### Running the MapReduce Word Count
1. Upload a text file to process:
   - Use the Colab file uploader to provide **uud-1945.txt** file.
2. Creating directory in HDFS
3. Copying the file from local file system to Hadoop distributed file system (HDFS)
4. Create Mapper File
5. Create Reducer File
6. Changing the permissions of the files
7. Running MapReduce Programs
8. Exploring the created output directory
9. Copy file **hdfs-wordcount.txt** dari HDFS ke local