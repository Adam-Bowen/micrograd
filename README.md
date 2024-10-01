# MicroGrad

⚙️ Autograd engine using backpropagation.

## Overview

MicroGrad is a lightweight autograd engine that implements backpropagation for automatic differentiation. This project is designed to provide a simple implementation of an autograd system, similar to those used in larger DL frameworks.

## Installation

1. Clone this repository
2. Install the required packages:
   ```
   pip install micrograd
   ``
   ```

## Tracing/Visualisation

```
from micrograd import nn
 n = nn.Neuron(2)
 x = [Value(1.0), Value(-2.0)]
 y = n(x)
 dot = draw_dot(y)
``
```

## Files

- `engine.py`: Contains the core implementation of the autograd engine.
- `nn.py`: Implements neural network components using the autograd engine.
