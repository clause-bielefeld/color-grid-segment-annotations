# Color Grids / Segment Annotations

## Preparing Data for LabelStudio
1. Sample games from McDowell & Goodman's Color Grid Data to use as input for Label Studio
    1. `generate_game_annotation_files/01_filter_games.ipynb`
    2. `generate_game_annotation_files/02_make_annotation_files.ipynb`

## Setting Up LabelStudio
- Configuration: `label_studio_config/labeling_interface.xml`
- Annotation guidelines: `guidelines/`

## Processing Annotations
1. Run `majority_vote.ipynb`

## Processed Data

File that contains the final data:
`data/processed_annotations/consensus_majority_clean.json`