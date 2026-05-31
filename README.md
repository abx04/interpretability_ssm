# Interpretability study of CodeSSM
We provide the code for kernel analysis and DirectProbe.

The results included in the paper are also provided. 

The DirectProbe results are available in the `DirectProbe results` directory.
The plots related to hidden representation analysis can be generated using `DirectProbe_plot.ipynb`.

To generate all the results of hidden representation analysis, download the weights of CodeSSM and RoCoder released by the authors of [CodeSSM](https://aclanthology.org/2025.emnlp-main.1735.pdf).

Then follow the steps from [Anand et.al](https://github.com/stg-tud/code-LLM-critical-evaluation) for "Probing on Hidden representation".

For the kernel analysis, use the weights from CodeSSM with `kernel_analysis_ssm.ipynb`.
