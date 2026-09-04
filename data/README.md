# Contents of this directory

- `color_grid_data.json`: Raw data from McDowell & Goodman, generated with the notebook `data_prep/process_colorgrid_data.ipynb` from this repo: https://github.com/clause-bielefeld/mllm-listeners ([link to notebook](https://github.com/clause-bielefeld/mllm-listeners/blob/main/data_prep/process_colorgrid_data.ipynb))
    - Repository with original data: [github.com/forkunited/ltprg](https://github.com/forkunited/ltprg)
- `sampled_annotations`: Sampled games from McDowell & Goodman, generated with the notebook `generate_game_annotation_files/02_make_annotation_files.ipynb`
- `filtered_gameids.json`: IDs of games with > 80% success rate, generated with the notebook `generate_game_annotation_files/01_filter_games.ipynb`
- `label_studio_input`: Inputs (images and json file for all games) for segment annotation with LabelStudio
- `raw_annotations`: Raw segment annotations (divided by annotators)
- `processed_annotations`: Processed segment annotations (aggregated with majority voting)
    - `consensus_majority_raw.json`: Without cleaned word boundaries
    - `consensus_majority_clean.json`: With cleaned word boundaries

## Note:

All files have been anonymized using pseudonyms, and links to the data storage repositories used during the annotation process have been replaced with placeholders.


# Copyright information for original dataset

MIT License

Copyright (c) 2019 Bill McDowell

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---------------

→ See [license information in the original repository](https://github.com/forkunited/ltprg/blob/master/LICENSE)