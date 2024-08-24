# Training a Transformer Decoder to Generate Text

The notebook `main.ipynb` contains 1) the building blocks for a Transformer Decoder in PyTorch, 2) code to load and preprocess text on which to train the Decoder, and 3) a training loop.

### Model

The notebook defines a Multi-Head Self Attention, a Decoder Block, etc just as defined in the original [Transformers paper](https://arxiv.org/pdf/1706.03762). These are also the building blocks for models in the GPT series.

### Dataset

The Decoder is currently trained on `taylor_swift_wiki.txt`, which is the raw text from Taylor Swift's [Wikipedia page](https://en.wikipedia.org/wiki/Taylor_Swift). However, this file can be substituted for any other raw text file.