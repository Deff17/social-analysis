Repository description:
* The repository can be divided into 3 main modules: jupyter, python and results.


The python module consists of:
   * clustering module - code for K-means and HDBSCAN clustering
   * database - code for filling database and executing queries
   * neighbourhood - code for calculating results for neighbourhood analysis
   * prediction - code for preparing predictions data
   * separation - module with code for feature separation analysis
   * stability - module with code for role stability analysis
   * utils - code with methods to write to files and mapping cluster numbers to role names


The jupyther module consists of:

   * FeatureTableCSV - names of features
   * GeneralSats.ipynb - scripts for calculating general statistics
   * Features.ipynb -  scripts for calculating features
   * FeatureCorrelation2.ipynb - scripts for calculating correlation between features 
   * TableGeneration.ipynb - scripts for filling a database with features calculated in Features.ipynb file
   * Separation.ipynb - scripts for calculating and testing separation of features
   * Stability.ipynb - scripts for calculating and testing stability of features

The results' module consists of:
   * HP\_global\_stats\_neighbourhood - statistics of neighbourhood analysis for Huffington Post
   * HP\_separation\_neighbourhood - statistics of neighbourhood separation for Huffington Post 
   * NORM\_STATS* -  normalized statistics of clusters
   * Salon\_Neighbourhood\_analysis - statistics of neighbourhood analysis for Salon 24
   * Salon\_separation\_features -  statistics of features separation analysis for Salon 24
   * Salon\_separation\_neighbourhood - statistics of neighbourhood separation analysis for Salon 24
   * clustering - results of clustering for Salon 24 and the Huffington Post \item feature\_selection\_hp - images of feature selection phase for the Huffington Post
   * feature\_selection\_salon - images of feature selection phase for the Salon 24
   * neighbourhood - results of neighbourhood analysis of the Salon 24 and the Huffington Post
   * prediction - results of prediction analysis of the Salon 24 and the Huffington Post
   * stability - results of stability analysis of the Salon 24 and the Huffington Post
