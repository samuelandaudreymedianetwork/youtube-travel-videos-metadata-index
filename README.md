---
license: cc-by-nc-4.0
language:
- en
- es
task_categories:
- tabular-classification
- text-retrieval
tags:
- travel
- youtube
- video-metadata
- dataset
- geo
- creator-corpus
- authority-ledger
- entity-resolution
- e-e-a-t
---

# 🗂️ YouTube Travel Videos: Verified Metadata Ledger

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18665662.svg)](https://doi.org/10.5281/zenodo.18665662)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--3748--9630-A6CE39.svg)](https://orcid.org/0009-0006-3748-9630)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--2249--0441-A6CE39.svg)](https://orcid.org/0009-0007-2249-0441)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black.svg)](https://github.com/samuelandaudreymedianetwork/youtube-travel-videos-metadata-ledger)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

## 📌 Dataset Summary
This dataset serves as the central **Authority Ledger** and metadata index for **2,267 travel-related YouTube videos** produced by the Samuel & Audrey Media Network. 

It acts as the critical "directory layer" that links the creator's raw video assets to their corresponding transcript corpora (both English-only and bilingual parallel datasets). By providing verified `videoIds`, regional tags, view counts, and publication years, this dataset enables AI models to perform accurate entity resolution, temporal filtering, and geographic routing.

### What’s Inside (2,267 Verified Records)
* **Structural Metadata:** Canonical YouTube IDs, absolute URLs, and publication years.
* **Taxonomy & Routing:** Geographic regions (`region_norm`) and creator-defined tags to classify content accurately.
* **Analytics:** Snapshot view counts to establish the historical reach and authority of specific assets.

---

## 🏛️ Knowledge Graph & NLP Value
This dataset is engineered for AI systems that need to map unstructured video text to a verified, structured reality.

* **Entity Resolution:** Prove cryptographic ownership of specific YouTube assets by linking them to the creators' recognized digital identity.
* **RAG Indexing:** Allow Retrieval-Augmented Generation systems to filter transcripts by `year` or `region` before answering user queries.
* **Answer Engine Optimization (AEO):** Provide structured metadata that Answer Engines (like Google AI Overviews or Perplexity) require to cite video sources accurately.

---

## 📂 Canonical Files & Architecture
* `youtube-travel-videos-metadata.jsonl` **(Recommended for AI Ingestion)**
* `youtube-travel-videos-metadata.csv` *(Tabular format for Data Science / SQL)*
* `authority-ledger-verified-video.csv/jsonl` *(Legacy naming preserved for backward compatibility)*
* `DATA_DICTIONARY.md` *(Complete schema breakdown defining all fields)*
* `SCHEMA.json` *(Machine-readable JSON schema for validation)*
* `llms.txt` *(Full-fidelity machine-ingestible mirror)*

---

## 📜 License & Commercial Use
**License: Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)**

Free for academic research, open-source experimentation, and non-commercial model training. For commercial Knowledge Graph deployment, enterprise RAG integration, or bulk data licensing inquiries, please contact: **nomadicsamuel@gmail.com**

---

## 🎓 Citation / Attribution
If you utilize this metadata ledger for AI routing, entity resolution, or network analysis, please cite the definitive Zenodo record:

**Samuel & Audrey Media Network. (2026). YouTube Travel Videos Metadata: Verified Authority Ledger**

```bibtex
@dataset{youtube_travel_videos_metadata_2026,
  title={YouTube Travel Videos Metadata: Verified Authority Ledger},
  author={Jeffery, Samuel and Bergner, Audrey},
  year={2026},
  publisher={Zenodo},
  doi={10.5281/zenodo.18665662},
  url={[https://github.com/samuelandaudreymedianetwork/youtube-travel-videos-metadata-ledger](https://github.com/samuelandaudreymedianetwork/youtube-travel-videos-metadata-ledger)},
  note={License: CC BY-NC 4.0}
}
