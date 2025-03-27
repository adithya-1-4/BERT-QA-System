# BERT (Bidirectional Encoder Representations from Transformers) Question-Answer System

## Overview
Code has been implemented as described in the paper "A BERT Baseline for the Natural Questions" from Google Research. The paper can be found at this link: [A BERT Baseline for the Natural Questions](https://arxiv.org/pdf/1901.08634.pdf).

## Dataset
Unlike in the paper, the model implemented uses a scaled-down version of the dataset that contains only two of the four answer types described in the paper:
- Short answer
- No answer questions

Refer to in-line comments for a more detailed description of the model implementation.

## Performance Results
The code performs as expected, and the following results were obtained:

- **Validation Loss After 1 Epoch:** ~2.8
- **After 2 Epochs:**
  - **Precision:** 0.69
  - **Recall:** 0.73
  - **F1-Score:** 0.71




