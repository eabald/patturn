# 🏺 Patturn

**Unsupervised Clustering of Pottery Decoration Motifs**
_A visual and analytical pipeline for identifying stylistic patterns in archaeological ceramics._

---

## 📖 Overview

**Patturn** is a modular pipeline for analyzing and clustering decorative motifs on pottery, with a primary focus on Late Neolithic to Early Bronze Age ceramics in Eastern Europe.

It combines image preprocessing, feature extraction, dimensionality reduction (UMAP), and unsupervised clustering (DBSCAN), culminating in interactive visualizations and metadata integration.

The goal is to assist archaeologists, digital humanists, and heritage researchers in:

- Discovering recurring stylistic motifs
- Exploring cross-cultural decorative influences
- Supporting typological classification with machine learning

---

## 🧪 Features

- ✅ Compatible with real or synthetic image datasets
- 🧠 UMAP projection for visual similarity analysis
- 📦 DBSCAN clustering with automatic outlier detection
- 🎨 Visualization by motif style and cluster ID
- 📊 Metadata-linked output (CSV export)
- 🖼️ Optional thumbnail-based plotting
- 📁 Ready-to-use with structured image folders + metadata

---

## 🔧 Installation (via Conda)

```bash
git clone https://github.com/yourusername/patturn.git
cd patturn
conda env create -f environment.yml
conda activate patturn
