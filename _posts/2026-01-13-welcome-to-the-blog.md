---
layout: post
title: "Welcome to the Blog"
subtitle: "A space for AI research insights and ML theory"
date: 2026-01-13
background: '/img/posts/welcome.jpg'
---

Welcome to my AI research blog! This is a space where I'll share thoughts on machine learning theory, deep learning, and the latest developments in AI research.

## What to Expect

Posts will cover topics such as:

- **Learning Theory**: Understanding generalization, sample complexity, and the theoretical foundations of ML
- **Optimization**: Gradient descent dynamics, convergence analysis, and loss landscapes
- **Neural Networks**: Architectures, expressivity, and training dynamics
- **Research Insights**: Commentary on interesting papers and emerging trends

## Code Examples

Posts may include code snippets. Here's a simple example:

```python
import torch
import torch.nn as nn

class SimpleNetwork(nn.Module):
    def __init__(self, input_dim: int, hidden_dim: int, output_dim: int):
        super().__init__()
        self.layers = nn.Sequential(
            nn.Linear(input_dim, hidden_dim),
            nn.ReLU(),
            nn.Linear(hidden_dim, output_dim),
        )

    def forward(self, x: torch.Tensor) -> torch.Tensor:
        return self.layers(x)
```

## Math Support

Jekyll with Kramdown supports LaTeX-style math. For example, the cross-entropy loss:

$$
\mathcal{L}(\theta) = -\frac{1}{N} \sum_{i=1}^{N} \sum_{c=1}^{C} y_{i,c} \log(\hat{y}_{i,c})
$$

Stay tuned for more content!
