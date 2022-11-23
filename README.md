# All-cause-mortality-fluctuation-across-Italian-regions
Here is the code to reproduce the results presented in "Reconstruction of the temporal correlation network of all-cause mortality fluctuation across Italian regions: the importance of temperature and among-nodes flux" by Guido Gigante and Alessandro Giuliani (https://arxiv.org/abs/2211.12395).

The code is just a self-consistent (apart from mostly standard imports) Jupyter notebook. The cells should be run roughly in order of appearance.

The analysis of the data (correlations, commuters' flux, etc.) relies heavily on pandas.
The fitting procedures, instead, rely heavily on Jax (to just-in-time compile and compute the gradients).

The notebook produces all the plots presented in the paper.

The data used are described in the paper. I provide a link to a personal copy of the data (see the notebook) to make it easier to reproduce the results.
