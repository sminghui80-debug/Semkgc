# SemKGC: Semantic Label Generation with LLMs for Knowledge Graph Completion

![SemKGC](./SemKGC.png)

## Overview

This repository contains the implementation of the paper SemKGC: Semantic-Aware Knowledge Graph Completion with Fine-Grained Relation Semantics. In this work, we propose a semantic-enhanced KGC framework that leverages fine-grained relation semantic representations and optimized training paradigms, achieving consistent performance gains across standard benchmarks.

## Requirements

- Python 3.7 or above
- Additional dependencies are listed in `requirements.txt`

All experiments are conducted on a machine with 4 Quadro RTX 8000 GPUs.

## Installation

1. Clone this repository

2. Install the required dependencies:

```sh
pip install -r requirements.txt
```

## Data preparation
The link to the datasets can be found in the [Google Drive folder](https://drive.google.com/drive/folders/1mFER0J8TmrtR18VBaKOc6_VYYnjb88uu?usp=sharing).

Download the datasets and extract them to the `data` folder to get the following directory structure:

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
