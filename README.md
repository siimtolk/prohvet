# prohvet

Simple timeline forecastor. Example project comparing Meta's Procvet library and the new functime, which can use Polars dataframe
and should be more performant.

### Development


First, create a conda environent with the neccesary packages installed


>> conda env create -f environment.yml

If smth changes:

>> conda env update --file environment.yml --prune

>> conda activate timeseries-forecasting


### Jupyter

>> python -m ipykernel install --user --name timeseries-forecasting --display-name "Python (timeseries-forecasting)"

>> jupyter notebook

It will open a browser webpage for you to start hacking.

We will store the notebooks under jupyter_notebook. When running inside a docker container you might need the token from docker logs output.
