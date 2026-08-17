# SemKGC: Semantic Label Generation with LLMs for Knowledge Graph Completion

![SemKGC](./SemKGC.png)

## Overview

This repository contains the implementation of the paper SemKGC: Semantic-Aware Knowledge Graph Completion with Fine-Grained Relation Semantics. In this work, we propose a semantic-enhanced KGC framework that leverages fine-grained relation semantic representations and optimized training paradigms, achieving consistent performance gains across standard benchmarks.

## Requirements

- Python 3.7 or above
- Additional dependencies are listed in `requirements.txt`


## Installation

1. Clone this repository

2. Install the required dependencies:

```sh
pip install -r requirements.txt
```

## Data preparation
All data processing is complete. The directory structure is illustrated below.

```
data
├── FB15k237
│   ├── entities.json
│   ├── inverse_relations.json
│   ├── test.json
│   ├── train.json
│   └── valid.json
├── WN18RR
│   ├── entities.json
│   ├── inverse_relations.json
│   ├── test.json
│   ├── train.json
│   └── valid.json
```

## Training and evaluation

The scripts to train and evaluate a model on the WN18RR and FB15k-237 datasets are available in the `scripts` folder.

## Acknowledgements
The code is partially borrowed from [SimKGC](https://github.com/intfloat/SimKGC).

## Citation
If you find this work useful, please consider citing:

```

```
