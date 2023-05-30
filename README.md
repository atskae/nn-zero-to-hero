# Neural Networks: Zero to Hero

Following Andrej Karpathy's video series [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)!
* Video series GitHub: https://github.com/karpathy/nn-zero-to-hero

This repository is just a messy collection of notes for myself.

## Setup

1. Install required Python packages:

```
pip install -r requirements.txt
```

2. Install [GraphViz](https://www.graphviz.org/download/):

```
sudo apt install graphviz
```

3. Install PyTorch.

Check which graphics card is on the machine by running:
```
sudo lshw -C video
```

The [PyTorch installation command](https://pytorch.org/get-started/locally/#linux-pip) will differ based on graphics card. Go to the PyTorch webpage to find the correct command.

4. Launch Jupyter Lab:

```
jupyter-lab
```

## Notebook

Import commonly-used Python packages into the notebook (hold the `Esc` key, then press `Ctrl` + `v`):
```python
import math
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
```
