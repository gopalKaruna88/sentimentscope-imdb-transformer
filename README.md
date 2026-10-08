# SentimentScope: IMDB Sentiment Analysis with a Transformer

A transformer trained from scratch in PyTorch to classify IMDB reviews as positive or negative.

- Dataset: IMDB (25,000 train / 25,000 test reviews)
- Tokenizer: bert-base-uncased, max length 128
- Model: 4-layer transformer, mean pooling + linear classification head
- Result: 77.08% test accuracy (target: >75%)

## Files
- `SentimentScope_starter.ipynb`: full code, outputs and conclusion
- `sentiment_model.pt`: trained model checkpoint (PyTorch state_dict)
