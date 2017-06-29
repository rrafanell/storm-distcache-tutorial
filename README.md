# Storm Distcache Example

A simple example to run a **Twitter wordcount** Storm topology tracking words defined in a *wordsToTrack* file stored in a Storm distributed BLOB storage.

## Requirements

* Java Oracle JDK 1.8 or similar
* Maven
* Docker

## Overview

The project includes a ***infrastructure*** directory helping to automatically spin a dockerized infrastructure (Zookeeper, Storm and Kafka) services to run the example.

```bash
├── README.md
├── infrastructure
├── storm-distcache-topology
└── twitter-kafka-producer
```

## Infrastructure

The easiest way to start the necessary infrastructure is by:
