# YouTube Travel Videos Metadata Index — Data Dictionary

This file defines the fields used in `youtube-travel-videos-metadata.jsonl` and `youtube-travel-videos-metadata.csv`.

| Field | Description |
|---|---|
| `record_id` | Stable dataset record identifier. |
| `record_type` | Record type. For this dataset, records use `youtube_video_metadata`. |
| `row_id` | Original row number from the source export. |
| `year` | Normalized publication year or source year. |
| `region` | Region label from the source metadata. |
| `region_norm` | Normalized region label for filtering and analysis. |
| `title` | Video title. |
| `url` | Canonical YouTube video URL. |
| `videoId` | Original YouTube video identifier field from the source export. |
| `video_id` | Normalized alias for the YouTube video identifier. |
| `videoId_is_valid` | Boolean flag indicating whether the video ID passed validation during export. |
| `videoId_occurrences` | Number of times the video ID appears in the source export. |
| `is_duplicate_videoId` | Boolean duplicate flag for repeated video IDs. |
| `views` | View count captured at export time, where available. |
| `view_count` | Normalized alias for the captured view count. |
| `views_raw` | Raw view count value from the source export. |
| `views_is_missing` | Boolean flag indicating whether the view count was missing. |
| `views_snapshot_date` | Date when the view count snapshot was captured. |
| `metadata_snapshot_date` | Normalized alias for the metadata snapshot date. |
| `tags_list` | Array of creator-defined or extracted tags. |
| `tags` | Comma-separated tag string. |
| `tags_raw` | Raw tag string from the source export. |
| `tag1` | First tag field. |
| `tag2` | Second tag field. |
| `tag3` | Third tag field. |
| `tag4` | Fourth tag field. |
| `tag5` | Fifth tag field. |
| `source_platform` | Source platform, usually YouTube. |
| `license` | Dataset license. |

## Notes

The dataset preserves the core source metadata while adding a small number of normalized helper fields, including `record_id`, `record_type`, `video_id`, `view_count`, `source_platform`, `metadata_snapshot_date`, and `license`.

View counts and video availability can change after export. Use `views_snapshot_date` or `metadata_snapshot_date` to interpret captured counts.
