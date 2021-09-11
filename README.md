# Matlab license log analyzer

Analyzes usage of Matlab components by users from the license server log file.

Just provide the `lm_TMW.log` file and
open [analysis-notebook.ipynb](analysis-notebook.ipynb) in this
folder. You must change the following line to load the log file you
provided:

```python
log_df = read_log_df("lm_TMW-2018-2021.log")
```

You can also [view and run the notebook on nbviewer](https://nbviewer.jupyter.org/github/cengique/matlab-license-log-analyzer/blob/main/analysis-notebook.ipynb).

Open [Issues](https://github.com/cengique/matlab-license-log-analyzer/issues) if you have comments or suggestions.
