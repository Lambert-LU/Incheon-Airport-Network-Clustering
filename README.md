# Incheon Airport Network Clustering Analysis

## Overview

This project provides a data-driven analysis of Incheon International Airport’s route network using clustering techniques. The objective is to identify structural differences between transfer-oriented and direct-demand markets and evaluate the airport’s role as a regional hub.

---

## Objectives

- Segment routes based on passenger flow characteristics  
- Identify transfer-driven vs. direct-demand markets  
- Evaluate the dual-structure network of Incheon Airport  
- Provide insights for route planning and hub strategy  

---

## Data

The dataset is provided by Incheon International Airport Corporation and includes:

- Passenger traffic (paid + free passengers)  
- Transfer passengers  
- Flight frequency  
- Route-level information  
- Arrival and departure data  

---

## Methodology

The analysis applies multiple clustering techniques:

- K-means clustering  
- PAM (Partitioning Around Medoids)  
- Hierarchical clustering  
- DBSCAN (for validation)

Key features used:

- Transfer rate  
- Total passenger volume  

Cluster quality is evaluated using:

- Elbow method  
- Silhouette score  

---

## Key Findings

- The network is best described by **two clusters (K = 2)**  
- **Cluster 1:** Transfer-oriented routes (higher transfer rates)  
- **Cluster 2:** Direct-demand routes (higher passenger volumes)  
- Silhouette scores (~0.72–0.73) indicate strong clustering quality  

---

## Business Insights

- Incheon Airport operates a **dual-structure network**:
  - Direct routes → stability & traffic volume  
  - Transfer routes → connectivity & long-haul expansion  

- Transfer traffic depends on a strong direct-demand base  
- Both systems are complementary and jointly enhance network value  

---

## Tools & Libraries

- R  
- ggplot2  
- cluster  
- factoextra  
- dplyr / tidyverse  

---

## Project Structure
