# Starting The Jupyter Notebook Server

Use `conda env list` to see a list of existing environments. Example:

```
wchristerson@Ws-MacBook-Pro jn-learning % conda env list
# conda environments:
#
                         /Users/wchristerson/anaconda3
                         /Users/wchristerson/anaconda3/envs/myenv
base                     /Users/wchristerson/miniforge3
                         /Users/wchristerson/tensorflow-test/env
```

Select an environment to use. Example:

```
conda activate /Users/wchristerson/anaconda3/envs/myenv
```

Start the server for the Jupyter notebook:

```
(myenv) wchristerson@Ws-MacBook-Pro jn-learning % jupyter notebook
```

This will start the Jupyter notebook and open a new tab in the browser with the Jupyter notebook.