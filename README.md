# Deep Learning Midterm — Spring 2026

This repository contains the Kaggle notebook and supporting files for my Deep Learning midterm project on **text-to-SVG generation**.

## Overview

The final system fine-tunes a Qwen2.5-based model for SVG generation under Kaggle compute constraints.  
The notebook supports two modes:

1. **Train / fine-tune from scratch**
2. **Skip fine-tuning and load the best saved model weights directly**

Currently the notebook is configured to work directly from weights. There are instructions to comment out certain parts to fine-tune.

## Model Weights

To save time, the notebook can load the final model weights directly instead of re-running fine-tuning.

### Public Kaggle model link
[Qwen2.5 Weights](https://www.kaggle.com/models/hashimzia1/qwen2-5best)

### Kaggle notebook path
Inside Kaggle, the weights are loaded from:

```text
/kaggle/input/models/hashimzia1/qwen2-5best/pytorch/default/2/qwen3b-ci
