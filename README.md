# yield-profile

Full Author List
----------------
* Kalyana B. Duggal
* Emmanuel Moya Cruz
* Adriana L. Jemison
* Yaning Liu
* Grace O. DeCostanza
* Cameron B. Berlin
* Paige E. Piszel
* Brandon Orzolek
* Weihao Zhu
* Madeline E. Rotella*
* Marisa C. Kozlowski*

  
Introduction
------------
We present Yield Profiles as an efficient way to obtain a mechanistic hypothesis.
A publication describing the implementation of yield fingerprints can be found at `https://doi.org/10.26434/chemrxiv-2025-mtljf`.

If you are using our method in your research, please remember to cite our publication.


Features
--------
Our method can be used to obtain mechanistic hypotheses for a set of elimination reaction conditions, or a C–H activation catalyst.

In order to use our program to develop a mechanistic hypothesis for a set of elimination reaction conditions:
1)	Run your conditions with the six elimination substrates shown in the main text.
2)	Record the yields for each substrate, and add these yields to a new row in our data table, making sure that the yields are in the correct order to correspond to each substrate.
3)	Save this table as a CSV file in identical form to our example. Make sure the first row contains headings for each substrate column (S1, S2, etc.)  Make sure there are no headings for the conditions.
4)	Replace our CSV file name with your CSV file name and run the program.
5)	Your data point will appear on the UMAP plot marked as “10”.  Check where it is clustered and where it is located on the plot for mechanistic information.

In order to use our program to develop a mechanistic hypothesis for an unknown C–H activation catalyst:
1)	Run a withdrawing, neutral, donating, and hindered substrate from your scope.  Make sure that these substrates are as alike as possible, while only varying the necessary steric/electronic parameter.  Record the yields
2)	Add these yields to a new row in our table
3)	Replace our CSV file name with your CSV file name and run the program.
4)	Your data point will appear on the UMAP plot marked as the highest number.  Check with which mechanism it is clustered and where it is located on the plot for mechanistic information.



Installation
---------------------
Jupyter notebook file can be downloaded.  To use the file, an environment needs to be created with several dependencies installed.  This can be done by installing python and anaconda.  Make sure the following dependencies are also installed by typing them into the command line:

Install pandas (https://pandas.pydata.org/docs/index.html):
```python
$pip install pandas
```

Install numpy (https://numpy.org/):
```python
$pip install numpy
```

Installing plotly express (https://plotly.com/python/plotly-express/):
```python
$pip install plotly_express==0.4.0
```

Installing matplotlib (https://matplotlib.org/):
```python
$pip install matplotlib
```

Installing sklearn (https://scikit-learn.org/stable/):
```python
$pip install scikit-learn
```

Installing UMAP (https://umap-learn.readthedocs.io/en/latest/):
```python
$pip install umap-learn
```


License
-------

Distributed under the terms of the `Apache 2.0 license`


Issues
------

If you encounter any problems,
please file an issue along with a detailed description.
