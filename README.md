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
```

## 🗂️ Project Structure

```bash
patturn/
│
├── data/                  # Raw or synthetic image data
├── metadata/              # Metadata CSVs
├── notebooks/             # Jupyter notebooks (pipeline, experiments)
├── outputs/               # Visualizations, clustered CSVs
├── environment.yml        # Conda environment spec
└── README.md
```

## 🚀 Usage

1. Place images into /data/, structured by motif class or unstructured (flat).

2. Provide a metadata CSV (or use synthetic generator).

3. Run the pipeline notebook in /notebooks/.

4. Analyze UMAP plots and clustering results.

5. Export or extend with your own classifiers or GIS integration.

## 📊 Example Output

- UMAP scatter plot of motifs

- DBSCAN cluster overlay with motif style coloring

- Cluster-wise breakdown subplots with shared legends

- Metadata-enriched CSV of cluster labels

## 🧱 Dependencies

Key libraries used:

- `numpy`, `pandas`

- `opencv-python`, `Pillow`

- `umap-learn`, `scikit-learn`

- `matplotlib`, `seaborn`

See `environment.yml` for full details.

## 🌍 Archaeological Context

Patturn is designed with the Eastern European context in mind, particularly decorative traditions in cultures such as:

- Funnelbeaker (TRB)

- Corded Ware

- Bell Beaker

- Lusatian

- Mierzanowice

However, the pipeline is fully adaptable to other regions, periods, or ceramic traditions.

---

## 📄 License

MIT License. See [LICENSE](LICENSE).

## 🤝 Acknowledgements

- Inspired by digital archaeology and computational typology research.

- UMAP and DBSCAN libraries provide the backbone of unsupervised analysis.

- Developed with support from academic collaboration and open-source ML tools.

## ✨ Future Work

- Real data integration

## 📬 Contact

For questions, ideas, or collaboration:

Maciej Krawczyk
Email: [maciej.krawczyk@uw.edu.pl](maciej.krawczyk@uw.edu.pl)
GitHub: @eabald
