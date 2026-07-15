# Fashion Recommendation System

## Overview

This project is a **content-based fashion recommendation system** built with the **DeepFashion2** dataset. It detects clothing items in an input image using **YOLO**, extracts visual features with **CLIP**, and retrieves the most similar clothing items using **FAISS**.

## Features

* Detect multiple clothing items in an image
* Extract visual embeddings using CLIP
* Fast similarity search with FAISS
* Return Top-K similar clothing recommendations

## Technologies

* Python
* YOLO
* CLIP
* FAISS
* PyTorch

## Pipeline

```text
Input Image
      ↓
YOLO Detection
      ↓
Crop Clothing
      ↓
CLIP Embeddings
      ↓
FAISS Search
      ↓
Top-K Recommendations
```

## Dataset

* **DeepFashion2**
