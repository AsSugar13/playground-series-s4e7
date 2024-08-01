## Kaggle competition solution
https://www.kaggle.com/competitions/playground-series-s4e7

### Project Goal
The objective of this competition is to predict which customers respond positively to an automobile insurance offer.

### Synthetically-Generated Datasets
Using synthetic data for Playground competitions allows us to strike a balance between having real-world data (with named features) and ensuring test labels are not publicly available. This allows us to host competitions with more interesting datasets than in the past. While there are still challenges with synthetic data generation, the state-of-the-art is much better now than when we started the Tabular Playground Series two years ago, and that goal is to produce datasets that have far fewer artifacts. Please feel free to give us feedback on the datasets for the different competitions so that we can continue to improve!

### keywords
torch, pytorch, autoencoder, embeddings

### Project methodology
Final model consists of separately trained embeddings with cosineembeddings loss and fullyconnected layers after. However you can consider more model tries like autoencoders in prototypes file.
