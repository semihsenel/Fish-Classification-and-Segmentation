# Fish Classification and Segmentation

## Classification

<img src="/images/Sample Red Sea Bream.png" alt="Red Sea Bream" width="300" height="300"/> <img src="/images/Sample Shrimp.png" alt="Shrimp" width="300" height="300">

<b>Shrimp</b>&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>Red Sea Bream</b>

</br></br>

- There are 9 different class of fishes.
- I used pretrained VGG model.
- I added couple of Dense layer and dropout layer.
- I implemented these by using PyTorch.

### Confusion Matrix

| Classes            | Precision | Recall | f1-score | Support |
|--------------------|-----------|--------|----------|---------|
| Black Sea Sprat    | 1.00      | 0.99   | 1.00     | 190     |
| Gilt-Head Bream    | 1.00      | 0.99   | 1.00     | 227     |
| Hourse Mackerel    | 0.99      | 0.99   | 0.99     | 193     |
| Red Mullet         | 0.95      | 1.00   | 0.97     | 176     |
| Red Sea Bream      | 0.98      | 1.00   | 0.99     | 185     |
| Sea Bass           | 1.00      | 1.00   | 1.00     | 215     |
| Shrimp             | 0.95      | 1.00   | 0.98     | 191     |
| Striped Red Mullet | 1.00      | 0.91   | 0.95     | 215     |
| Trout              | 1.00      | 1.00   | 1.00     | 208     |
|                    |           |        |          |         |
| accuracy           |           |        | 0.99     | 1800    |
| macro avg          | 0.99      | 0.99   | 0.99     | 1800    |
| weighted avg       | 0.99      | 0.99   | 0.99     | 1800    |
