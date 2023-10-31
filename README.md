# [Guiding LLM to Fool Itself: Automatically Manipulating Machine Reading Comprehension Shortcut Triggers](https://arxiv.org/abs/2310.18360)

## TL;DR 
This study exposes the vulnerabilities of Large Language Models (LLMs) in Machine Reading Comprehension tasks, focusing on their reliance on shortcuts. The research utilizes GPT-4 both as an editor to insert shortcut triggers in texts and as a reader to respond to questions. The study reveals that GPT-4 can successfully insert shortcut triggers that deceive even itself, resulting in a 15% drop in F1 score. A framework for this editing process is introduced, and we release ShortcutQA, a dataset for future research. Accepted to EMNLP Findings 2023.

## Repository Contents

### Files
- `Eval script.ipynb`: Jupyter notebook for evaluating the performance of LLMs on ShortcutQA.
- `Generate ShortcutQA.ipynb`: Jupyter notebook for generating the ShortcutQA dataset.
- `requirments.txt`: List of Python packages required to run the notebooks.
- `ShortcutQA1.csv`: The initial version of the ShortcutQA dataset.
- `ShortcutQA1_1.csv`: A newer version of the ShortcutQA dataset, recommended for future research.

### How to Use
1. **Installation**: Run `pip install -r requirments.txt` to install all required packages.
2. **Generate Dataset**: Open and run `Generate ShortcutQA.ipynb` to create the ShortcutQA dataset.
3. **Evaluation**: Open and run `Eval script.ipynb` to evaluate an LLM's performance on ShortcutQA.

## Citing This Work
If you find this work useful for your research, please consider citing our paper.

```bibtex
@misc{levy2023guiding,
    title={Guiding LLM to Fool Itself: Automatically Manipulating Machine Reading Comprehension Shortcut Triggers},
    author={Mosh Levy and Shauli Ravfogel and Yoav Goldberg},
    year={2023},
    eprint={2310.18360},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```

