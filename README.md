
# Multi-Task Recommender System

This project focuses on building a Multi-Task Recommender System that leverages NGCF (Neural Graph Collaborative Filtering) and ESMM (Entire Space Multi-Task Model) for Click-Through Rate (CTR) prediction. The system is designed to predict both user likes and clicks to enhance the recommendation process.

## Problem Statement

Traditional recommender systems often target a single objective, such as click prediction. However, in many scenarios, predicting multiple tasks, such as both clicks and likes, can provide a more comprehensive understanding of user preferences.

## Models Used

1. **NGCF (Neural Graph Collaborative Filtering):**
   - NGCF is employed for collaborative filtering to capture complex user-item interactions using graph neural networks.

2. **ESMM (Entire Space Multi-Task Model):**
   - ESMM is used for multi-task learning, allowing the model to jointly predict clicks and likes, optimizing for both objectives simultaneously.
