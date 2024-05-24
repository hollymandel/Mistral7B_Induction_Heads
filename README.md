This is a repo to locate <a href = "https://transformer-circuits.pub/2022/in-context-learning-and-induction-heads/index.html">induction heads</a> in <a href = "https://mistral.ai/news/announcing-mistral-7b/">Mistral 7B</a> (`ih_sweep.ipynb`) and then study the impact of ablating them on a question-answering task (`ih_babi.ipynb`). The dictionaries `ih_evaluators.pkl` and `ih_scores.pkl` contain the output of `ih_sweep.ipynb`, and `ih_scores.pkl` is necessary to run `ih_babi.pynb`.
