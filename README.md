# AI Study

A weekly deep learning study group run by the **GDG (Google Developer Group) Hongik University** chapter. We take a top-down approach — starting from the big picture of how models make predictions, then working our way down into the theory and math behind deep learning.

## About

This repository tracks our weekly sessions: lecture notebooks, hands-on exercises, and personal write-ups (WIL — *What I Learned*) from each member. The curriculum moves from classical machine learning foundations into neural networks and modern deep learning architectures.

## Structure

Each week has its own folder containing that session's materials:

```
weekN/
├── weekN.ipynb   # lecture notebook & hands-on practice
├── wil.md        # what-I-learned write-up
└── imgs/         # supporting images/diagrams
```

## Curriculum

| Week | Topic |
| ---- | ----- |
| 1 | How models make predictions — ML review, train/val/test splits, and an introduction to artificial neural networks (ANNs) |

*(updated as new sessions are added)*

## Tech Stack

- Python 3.12+
- TensorFlow
- scikit-learn
- Jupyter Notebook
- matplotlib
- [uv](https://github.com/astral-sh/uv) for dependency management

## Getting Started

```bash
# install dependencies
uv sync

# launch Jupyter
uv run jupyter notebook
```

## Contributing

Each member commits their own notebook and WIL notes under their week's folder after every session.
