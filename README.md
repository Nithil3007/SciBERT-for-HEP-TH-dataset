In general domains, large-scale training data is often possible to obtain, but gathering large-scale data and performing preprocessing is challenging and expensive.
BERT makes use of Transformer, an attention mechanism that learns contextual relations between words in a text. The Transformer encoder reads the entire sequence of words at once and labelling of a particular term in a sentence is done based on the words present before and after. This characteristic allows the model to learn the context of a word based on all of its surroundings.

SCIBERT, a pre-trained language model based on BERT performs unsupervised pre-training on an extensive multi-domain corpus of scientific publications to improve performance on NLP tasks involving scientific terms. SCIBERT follows the same architecture as BERT but is instead pretrained on scientific text. SCIBERT uses full text samples of 1.14M papers from Semantic Scholar- a corpus consisting of 18% papers from the computer science domain and 82% from the broad biomedical domain. The average paper length is 154 sentences (2,769 tokens) resulting in a corpus size of 3.17B tokens, similar to the 3.3B tokens on which BERT was trained.

## Results
The weights from training are stored to get the performance metrics for the testing batch.
The final Training Loss, Training Accuracy, Validation Loss and Validation Accuracy for the five batches are obtained. For every epoch, the batch-wise results of validation accuracy and validation loss are plotted.
![image](https://github.com/Nithil3007/SciBERT-for-HEP-TH-dataset/assets/102175607/51bb2005-563c-4100-bd16-ed1b6184d62f)
