Code has been implemented as described in the paper "A BERT Baseline for the Natural Questions" from Google Research. The paper can be found at this link https://arxiv.org/pdf/1901.08634.pdf.

Unlike in the paper, the model implemented used a scaled down version of the dataset that contains only two of the four answer types described in the paper - short answer and no answer questions. Look at in-line comments for more detailed description of model implementation.

The code performs as expected and the following results were obtained:

VALIDATION LOSS After 1 Epoch: ~2.8

After 2 Epochs:

PRECISION: 0.69

RECALL: 0.73

F1-SCORE: 0.71


