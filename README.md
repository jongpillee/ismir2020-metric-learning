# ismir2020-metric-learning
ISMIR 2020 Tutorial for Metric Learning in MIR

- [Jongpil Lee](https://jongpillee.github.io/)
- [Brian McFee](https://brianmcfee.net)
- [Juhan Nam](https://mac.kaist.ac.kr/~juhan/)

# Using these materials

## Option 1: Google Colab

The easiest way to follow along with the coding session of the tutorial is to use Google Colab's notebook server.  This will require a Google account, but you will not need to install any software on your own machine.

For the first coding demo, follow this link: http://bit.ly/ml4mir-demo-1

For the second coding demo, follow this link: http://bit.ly/ml4mir-demo-2

To use the code, you will need to click the "Connect" button: 

![Colab Connect button](colab-connect.png)

After clicking this button and waiting a few seconds, you should have an active notebook instance.
You may observe a warning message because the notebook was developed by us (and not Google) -- that's normal.  As long as you trust us to write reasonable code, feel free to accept the warning and continue. :grin:

You can then work through the notebook by executing each cell with the "play" button or by hitting `Shift+Enter`.


## Option 2: Local conda environment

If you'd prefer to run the code on your own machine, take the following steps.

1. Clone this repository.
2. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).
3. Create a conda environment from the environment specification provided by `metriclearningmir.yml` in this repository.  This is done by executing the following command:

```
conda env create -f metriclearningmir.yml
```

4. Activate the environment: 
```
conda activate metriclearningmir
```

5. You should now be able to run the `Metric Learning Demo.ipynb` or `Deep Metric Learning Demo.ipynb` notebook in Jupyter:
```
jupyter notebook "Metric Learning Demo.ipynb"
```
or 
```
jupyter notebook "Deep Metric Learning Demo.ipynb"
```
You may be prompted to change the environment for the notebook when it loads: if so, select `metriclearningmir` and you should be all set.


## Option 3: pip

If you prefer to not use conda environments, and already have a working Python
(3.6+) installation, you can instead perform the following steps:

1. Clone this repository.
2. Run the command `pip install -r requirements.txt` (from inside the repository
   directory).

You can then run
```
jupyter notebook "Metric Learning Demo.ipynb"
```
or 
```
jupyter notebook "Deep Metric Learning Demo.ipynb"
```
just as in the directions above for `conda`.

Happy hacking!
