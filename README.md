## Data import - Vector provision options in Weaviate

### Overview

When importing objects into Weaviate, you can choose to provide object vectors to Weaviate, or configure a Weaviate vectorizer to obtain vectors at import time. You can even combine these options to configure a vectorizer while explicitly providing vectors. 

### Accompanying video

> Note: This Jupyter notebook is an accompaniment to our video tutorial on the topic, which can be found at https://www.weaviate.io/developers/weaviate/tutorials/vector-provision-options

### Dataset

The "winemag_tiny.csv" file contains a tiny subset of "Wine Reviews" dataset from Kaggle. You can find the full dataset here (https://www.kaggle.com/datasets/zynicide/wine-reviews).
