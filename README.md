# GQA generalization data splits
GQA generalization splits used in ["Visually Grounded VQA by Lattice-based Retrieval", Reich et al.](http://arxiv.org/abs/2211.08086).
Splits are based on GQA's balanced data set, downloadable [here](https://cs.stanford.edu/people/dorarad/gqa/download.html).

Each file in the .zip contains a list of question IDs for its named subset. Question IDs are either from GQA balanced train set or val set (no mixing).

| Split | Train | Val |
| ----------- | ----------- | ----------- |
| "Objects" | 763k | 23k |
| "LingVariants | 801k | 20k |
| "Answers" | 862k | 11k |
| "LowResource" | 311k | 132k [^1] |

[^1]: The regular/original GQA balanced val set, not included for download here, grab from original GQA dataset release.
