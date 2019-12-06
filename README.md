# Sentence to Emoji Translation
A naive chunking approach to summarizing a sentence to emoji translation using sent2vec and some of emoji2vec's dataset. This is a final senior research project for my undergraduate degree at Clarion University. The paper and explanation of the algorithm can be seen at [TEMPORARY LINK](https://www.authorea.com/users/269084/articles/396929-sentence-to-emoji-translation). 

## Folder Structure
- `EmojiTranslation` -> Emoji Translation module
- `JupyterNotebooks` -> Literate programming-esque emoji translation algorithm
- `plots` -> Plots for the paper

## Getting off the Ground
- This project requires Python 3
- Install dependencies with `pip install -r requirements.txt`
- Download a [sent2vec model](https://github.com/epfml/sent2vec/tree/6b0eddec0c95e6e7f6f06582700305957311bfb9) to the models/directory
- Download the [emoji2vec dataset](https://github.com/uclnlp/emoji2vec/blob/fd3dcb60a06b530c755ed1f1c8157d505b80e844/data/raw_training_data/emoji_joined.txt) to the data/ directory
- `cd JupyterNotebooks && jupyter notebook` to start the jupyter notebook server to explore the algorithm
