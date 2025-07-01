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

There are two ways to use our code.  The first way is by downloading the jupyter notebook, and making sure pandas (https://pandas.pydata.org/docs/index.html), numpy (https://numpy.org/), plotly express (https://plotly.com/python/plotly-express/), matplotlib (https://matplotlib.org/), and sklearn (https://scikit-learn.org/stable/) are installed.  Using this method with the given versions will provide the best reproducibility of all the statistical analysis of our data.  The versions used in the original code are shown below:
Python version: 3.7
NumPy version: 1.21.5
Pandas version: 1.3.5
Scikit-learn version: 1.0.2

A much simpler way to use our code is by running it from this google colab link:
https://colab.research.google.com/drive/1lpNB9eyb6NbCjJiDg6dbxWiLqkhallVI?usp=sharing
This method utilizes much newer software versions, which may provide very minor discrepancies from our original analysis.  However, Colab is ideal for quick use of our method, as it does not require downloading python or any dependencies, and can be done directly from a web browser.  To run code in google colab, simply open the link, upload all required files directly into Colab, and run the first block of code.

License
-------

Distributed under the terms of the `Apache 2.0 license`


Issues
------

If you encounter any problems,
please file an issue along with a detailed description.
