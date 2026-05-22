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
- travel-videos
- creator-archive
- metadata-index
- video-archive
- argentina
- patagonia
- bilingual-media
- retrieval
size_categories:
- 1K<n<10K
---

# YouTube Travel Videos Metadata Index

This dataset contains structured metadata for **2,267 travel-related YouTube videos** published by the Samuel & Audrey Media Network.

It includes video identifiers, source URLs, publication years, regional tags, creator-defined topic tags, language context where available, and view counts captured at export time. The dataset is designed as a metadata index for organizing, searching, and connecting video records with related transcript datasets, travel archives, article corpora, and destination research.

This dataset does **not** contain video files. It provides metadata and source references for public YouTube videos.

## Canonical links

- Hugging Face dataset: https://huggingface.co/datasets/samuelandaudreymedianetwork/youtube-travel-videos-metadata-index
- GitHub repository: https://github.com/samuelandaudreymedianetwork/youtube-travel-videos-metadata-index
- Zenodo DOI: https://doi.org/10.5281/zenodo.18665662

## Dataset contents

| Record type | Count |
|---|---:|
| `youtube_video_metadata` | 2,267 |

## Snapshot details

| Field | Value |
|---|---:|
| Total video records | 2,267 |
| Valid YouTube video IDs | 2,267 |
| Duplicate video ID flags | 112 |
| Records with missing view counts | 4 |

## Most common normalized regions

| Region | Records |
|---|---:|
| `argentina` | 437 |
| `canada` | 306 |
| `south korea` | 164 |
| `peru` | 117 |
| `japan` | 98 |
| `global` | 72 |
| `germany` | 59 |
| `india` | 56 |
| `malaysia` | 54 |
| `japon` | 49 |
| `italy` | 46 |
| `uk` | 45 |

## What is included

- YouTube video IDs
- Canonical YouTube URLs
- Video titles
- Publication year
- Region and normalized region fields
- Creator-defined topic tags
- View counts at export time, where available
- Metadata snapshot date
- Duplicate and validity flags for video IDs
- JSONL and CSV formats
- Data dictionary, schema, citation file, license, checksums, and llms files

Each JSONL or CSV row represents one video metadata record.

## Related datasets

This metadata index can be used alongside related transcript corpora and travel archives from the Samuel & Audrey Media Network, including English transcript datasets, Spanish-English transcript datasets, article corpora, and destination-specific archives.

## Limitations

This dataset contains metadata and source URLs, not video files.

View counts, video availability, titles, descriptions, tags, and other YouTube metadata may change after export. Some videos may become unavailable, private, removed, renamed, or updated after the dataset was created.

Regional tags and topic tags may be derived or normalized for archive organization and should be reviewed before use in formal research.

The dataset should not be treated as a complete or current travel guide. Travel logistics, prices, routes, businesses, and destination conditions may have changed since the original videos were published.

## Files

- `youtube-travel-videos-metadata.jsonl` — canonical structured video metadata records
- `youtube-travel-videos-metadata.jsonl.gz` — compressed JSONL
- `youtube-travel-videos-metadata.csv` — spreadsheet-friendly export
- `youtube-travel-videos-metadata.csv.gz` — compressed CSV
- `DATA_DICTIONARY.md` — field definitions
- `SCHEMA.json` — machine-readable schema
- `CITATION.cff` — citation metadata
- `LICENSE.txt` — license text
- `MANIFEST.json` — package manifest
- `SHA256SUMS.txt` — file checksums
- `llms.txt` — short machine-readable dataset guide
- `llms-youtube-travel-videos-metadata-index.txt` — full plain-text export

## Notes on cleanup and naming

Earlier internal exports included duplicate files with legacy names. Those duplicate files are not included in this cleaned package. The canonical data files use the `youtube-travel-videos-metadata` naming pattern.

## License

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

For commercial licensing inquiries, expanded usage rights, or partnership questions, contact nomadicsamuel@gmail.com.

## Citation

Samuel & Audrey Media Network. (2026). *YouTube Travel Videos Metadata Index*. Zenodo. https://doi.org/10.5281/zenodo.18665662
