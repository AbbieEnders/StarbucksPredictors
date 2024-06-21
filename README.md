# StarbucksPredictors
## Project Overview
- Starbucks collects data on offers and purchase transactions for their Rewards Members
- Will this data inform purchase transactions? Can we predict the transaction of a customer based on their demographic data?
- The expectation is that a classifier model will explore in the interaction in the app is able to be connected to the demographic data.
    - We will explore this success with the Accuracy, Precision, and F-1 score, as well as a confusion matrix with the withheld test dataset.
    - An F-1 score is great for classification because it allows us to evaluate precision and recall in one value. A better F-1 score means a more well performing model. 
- The regression model will determine if demographic data can predict the transaction amount.
    - For regression we can explore the R-squared score and residuals. This shows how much of the amount of the transaction isn't captured by the model for the test data.
## Where are the results?
Review a detailed review on Medium [add link].
## How do I use this?
You can download this notebook and see the code run.
### Dependencies
Versions of the packages in my virtual environment, starred ones called specifically in my project.
# Name                    Version                   Build  Channel
asttokens                 2.4.1              pyhd8ed1ab_0    conda-forge
bzip2                     1.0.8                hcfcfb64_5    conda-forge
ca-certificates           2024.6.2             h56e8100_0    conda-forge
colorama                  0.4.6              pyhd8ed1ab_0    conda-forge
comm                      0.2.2              pyhd8ed1ab_0    conda-forge
contourpy                 1.2.1                    pypi_0    pypi
cycler                    0.12.1                   pypi_0    pypi
debugpy                   1.8.1           py312h53d5487_0    conda-forge
decorator                 5.1.1              pyhd8ed1ab_0    conda-forge
exceptiongroup            1.2.0              pyhd8ed1ab_2    conda-forge
executing                 2.0.1              pyhd8ed1ab_0    conda-forge
fonttools                 4.53.0                   pypi_0    pypi
importlib-metadata        7.1.0              pyha770c72_0    conda-forge
importlib_metadata        7.1.0                hd8ed1ab_0    conda-forge
ipykernel                 6.29.4             pyh4bbf305_0    conda-forge
ipython                   8.25.0             pyh7428d3b_0    conda-forge
jedi                      0.19.1             pyhd8ed1ab_0    conda-forge
joblib                    1.4.2                    pypi_0    pypi
jupyter_client            8.6.2              pyhd8ed1ab_0    conda-forge
jupyter_core              5.7.2           py312h2e8e312_0    conda-forge
kiwisolver                1.4.5                    pypi_0    pypi
krb5                      1.21.2               heb0366b_0    conda-forge
libexpat                  2.6.2                h63175ca_0    conda-forge
libffi                    3.4.2                h8ffe710_5    conda-forge
libsodium                 1.0.18               h8d14728_1    conda-forge
libsqlite                 3.46.0               h2466b09_0    conda-forge
libzlib                   1.3.1                h2466b09_1    conda-forge
matplotlib**              3.9.0                    pypi_0    pypi
matplotlib-inline**       0.1.7              pyhd8ed1ab_0    conda-forge
nest-asyncio              1.6.0              pyhd8ed1ab_0    conda-forge
numpy**                   2.0.0                    pypi_0    pypi
openssl                   3.3.1                h2466b09_0    conda-forge
packaging                 24.1               pyhd8ed1ab_0    conda-forge
pandas**                  2.2.2                    pypi_0    pypi
parso                     0.8.4              pyhd8ed1ab_0    conda-forge
pickleshare               0.7.5                   py_1003    conda-forge
pillow                    10.3.0                   pypi_0    pypi
pip                       24.0               pyhd8ed1ab_0    conda-forge
platformdirs              4.2.2              pyhd8ed1ab_0    conda-forge
prompt-toolkit            3.0.47             pyha770c72_0    conda-forge
psutil                    5.9.8           py312he70551f_0    conda-forge
pure_eval                 0.2.2              pyhd8ed1ab_0    conda-forge
pygments                  2.18.0             pyhd8ed1ab_0    conda-forge
pyparsing                 3.1.2                    pypi_0    pypi
python                    3.12.4          h889d299_0_cpython    conda-forge
python-dateutil           2.9.0.post0              pypi_0    pypi
python_abi                3.12                    4_cp312    conda-forge
pytz                      2024.1                   pypi_0    pypi
pywin32                   306             py312h53d5487_2    conda-forge
pyzmq                     26.0.3          py312hd7027bb_0    conda-forge
scikit-learn**            1.5.0                    pypi_0    pypi
scipy                     1.13.1                   pypi_0    pypi
setuptools                70.1.0             pyhd8ed1ab_0    conda-forge
six                       1.16.0             pyh6c4a22f_0    conda-forge
stack_data                0.6.2              pyhd8ed1ab_0    conda-forge
threadpoolctl             3.5.0                    pypi_0    pypi
tk                        8.6.13               h5226925_1    conda-forge
tornado                   6.4.1           py312h4389bb4_0    conda-forge
traitlets                 5.14.3             pyhd8ed1ab_0    conda-forge
typing_extensions         4.12.2             pyha770c72_0    conda-forge
tzdata                    2024.1                   pypi_0    pypi
ucrt                      10.0.22621.0         h57928b3_0    conda-forge
vc                        14.3                h8a93ad2_20    conda-forge
vc14_runtime              14.40.33810         ha82c5b3_20    conda-forge
vs2015_runtime            14.40.33810         h3bf8584_20    conda-forge
wcwidth                   0.2.13             pyhd8ed1ab_0    conda-forge
wheel                     0.43.0             pyhd8ed1ab_1    conda-forge
xz                        5.2.6                h8d14728_0    conda-forge
zeromq                    4.3.5                he1f189c_4    conda-forge
zipp                      3.19.2             pyhd8ed1ab_0    conda-forge
### Files in the repo
Starbucks_capstone_notebook.ipynb -> Jupyter Notebook used to analyze the mock-Starbucks user data.

data/portfolio.json-> offer information

data/profile.json-> user information

data/transcript.json-> interaction information
