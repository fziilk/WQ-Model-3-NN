[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fziilk/tldi2_release/blob/dev/TLDI2.ipynb)
[![GitHub repo size](https://img.shields.io/github/repo-size/fziilk/tldi2_release)](https://github.com/fziilk/tldi2_release)
[![GitHub language count](https://img.shields.io/github/languages/count/fziilk/tldi2_release)](https://github.com/fziilk/tldi2_release)

# WQ-Model-3-NN
Water Quality Model Neural Networks

## Model Architecture
<a href="https://github.com/fziilk/WQ-Model-3-NN">
  <img src="https://raw.githubusercontent.com/fziilk/WQ-Model-3-NN/refs/heads/master/architecture_alpha.png" alt="M3" width="1000" align="center"/>
</a>

## Model Evaluation
```python
                precision    recall  f1-score   support

  not potable     0.74      0.84      0.79        63
      potable     0.66      0.50      0.57        38

     accuracy                         0.71       101
    macro avg     0.70      0.67      0.68       101
 weighted avg     0.71      0.71      0.70       101
```

## Testing
Visit the [evaluation notebook](https://github.com/fziilk/WQ-Model-3-NN/blob/master/EVAL_MODEL3_NN_WQ.ipynb) to see how to load and get predictions from both version of the TLDI model.