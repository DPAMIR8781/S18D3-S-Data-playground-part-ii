# Deep Learning Playground Part II

## Project Overview
This project explores how different deep learning hyperparameters affect neural network convergence, stability, overfitting, and generalization using TensorFlow Playground.

The notebook focuses on understanding the behavior of neural networks by experimenting with:

- Batch Size
- Regularization (L2)
- Learning Rate

The goal is to visually analyze how these parameters impact training and validation performance and connect Playground experiments with practical Keras concepts.

---

## Objectives

- Understand convergence behavior in neural networks
- Observe overfitting and underfitting scenarios
- Analyze the effect of batch size on training stability
- Learn how L2 regularization improves generalization
- Explore the impact of learning rate on optimization
- Translate Playground architectures into Keras-ready thinking

---

## Technologies Used

- Python
- TensorFlow Playground
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Topics Covered

### 1. Batch Size
Experiments were performed with different batch sizes to observe:

- Stable vs noisy gradient updates
- Training convergence speed
- Loss fluctuations
- Generalization behavior

Key observation:
- Small batch sizes produced noisier training.
- Larger batch sizes resulted in smoother convergence.

---

### 2. Regularization (L2)
L2 regularization was applied to reduce overfitting.

Observed effects:
- More stable validation loss
- Better generalization
- Reduced model complexity
- Prevention of aggressive weight growth

---

### 3. Learning Rate
Different learning rates were tested and compared visually.

Findings:
- Very small learning rates caused slow learning.
- Moderate learning rates achieved optimal convergence.
- Extremely high learning rates caused divergence and unstable loss behavior.

A visualization of:
- `Learning Rate vs Test Loss`
was created using Matplotlib.

---

## Example Visualization

```python
learning_rates = [0.0001, 0.001, 0.01, 0.1, 1.0, 10.0]
test_loss = [0.48, 0.22, 0.08, 0.15, 1.8, 8.5]
```

---

## Project Structure

```bash
S18D3-S-Data-playground-part-ii/
│
├── playground_part_2.ipynb
├── README.md
└── images/
```

---

## Key Concepts Learned

- Convergence
- Overfitting
- Underfitting
- Gradient Noise
- Generalization
- Hyperparameter Tuning
- L2 Regularization
- Learning Rate Optimization

---

## Conclusion

This project provided practical intuition about how neural network hyperparameters influence model behavior. By experimenting visually in TensorFlow Playground and analyzing the results, deeper understanding of optimization and training dynamics was achieved.

---

## Author

**Doruk Pamir**

GitHub:
https://github.com/DPAMIR8781
