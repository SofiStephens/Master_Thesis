# Evaluation of stereotypical biases in recent GPT models 
### Master Thesis - M.Sc. Business Intelligence and Process Management 
### HWR Berlin

The original datasets are in [benchmarks](benchmarks) folder, including a [quality assesment of CrowS-Pairs](benchmarks\CrowS-Pairs\crows_pairs_quality_check.ipynb). The EDA and pre-processing is in [EDA_Preprocessing.ipynb](EDA_Preprocessing.ipynb).
The completions for the RQ1 are performed in [RQ1completions.ipynb](RQ1completions.ipynb) and stored in [data\RQ1](data\RQ1). The analysis of the responses is in [results_analysis\RQ1](results_analysis\RQ1), including the [undetermined responses labeling](results_analysis\RQ1\label_undetermined_responses).
After the analysis of RQ1, as as part of the adversarial attack of RQ2, the models are asked the words that contributed the most to their response in [get_important_words.ipynb](get_important_words.ipynb) and they are stored in [data\RQ2\important_words](data\RQ2\important_words).
With the important words, the adversarial examples are constructed in [adversarial_examples.ipynb](adversarial_examples.ipynb) and stored in [data\RQ2\adv_sentences](data\RQ2\adv_sentences).
Finally, a new round of completions is conducted with the adversarial examples in [RQ2completions.ipynb](RQ2completions.ipynb). The responses are stored in [data\RQ2\adv_completions](data\RQ2\adv_completions) and analysed in [results_analysis\RQ2](results_analysis\RQ2).
