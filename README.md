# ST-Crisis Dataset

This repository contains the anonymized review version of the **ST-Crisis** benchmark dataset introduced in:

> *ST-Crisis: A Diagnostic Benchmark for Spatiotemporal Grounding in Crisis Communication*

## Overview

ST-Crisis is a benchmark dataset designed to evaluate spatiotemporal grounding and reasoning capabilities in crisis response systems.

The dataset is constructed from crisis-related social media posts and includes:
- Situational Awareness (SA) posts enriched with spatial and temporal information
- Crisis Need (CN) queries synthesized for diagnostic evaluation
- Multiple disaster scenarios:
  - Floods
  - Wildfires
  - Hurricanes

The benchmark supports evaluation of:
- Retrieval quality
- Spatial grounding
- Temporal grounding
- Response generation quality

## Dataset Structure

```text
ST-Crisis-Dataset/
├── Flood_CN queries.xlsx
├── Flood_SA tweets.xlsx
├── Hurricane_CN queries.xlsx
├── Hurricane_SA tweets.xlsx
├── Wildfire_CN queries.xlsx
└── Wildfire_SA tweets.xlsx
