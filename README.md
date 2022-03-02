# Bert-Extract-Features

### The extract_features.py file in [BERT repo](https://github.com/google-research/bert) uses `tf.data.Dataset.from_tensor_slices`. Because of this, the script fails to extract features for a large dataset.
### The current script uses TFRecordReader that fixes the issue allowing extraction of features from a larger dataset.





