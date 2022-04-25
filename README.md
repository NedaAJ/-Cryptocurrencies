# Cryptocurrencies
## Analysis Overview
The goal of this project is to utilize unsupervised machine learning to evaluate a cryptocurrency database and provide a report that categorizes traded cryptocurrencies into groups based on their characteristics.
An investment bank might utilize this categorization report to propose a new bitcoin investment portfolio to its clients.
For the analysis, we employ the following methods:
- Preprocessing the database
- Principal Component Analysis to reduce data dimension
- K-Means to cluster cryptocurrencies
- 2D and 3D scatter plots to visualize classification results

## Results
We now have a total of 532 marketable cryptocurrencies after the preprocessing and cleaning step.

### Clustering Cryptocurrencies using K-Means - Elbow Curve

We don't know what the analysis' outcome will be, thus we're utilizing unsupervised machine learning to find cryptocurrency clusters.
The elbow curve below was created using the K-Means approach with k values ranging from 1 to 10.

<p align="center">
  <img src="https://github.com/NedaAJ/Cryptocurrencies/blob/main/Resources/Elbow_curve.PNG"> 
</p>

The optimal k number looks to be 4, thus we'll classify the cryptocurrencies using an output of four clusters.


### Visualizing Cryptocurrencies Results
#### 3D-Scatter plot with clusters
<p align="center">
  <img src="https://github.com/NedaAJ/Cryptocurrencies/blob/main/Resources/3D-Scatter_Clusters.png"> 
</p>
The PCA technique was used to reduce the crytocurrencies dimensions to three principal components, resulting in this 3-D scatter plot.

#### Tradable Cryptocurrencies Table
<p align="center">
  <img src="https://github.com/NedaAJ/Cryptocurrencies/blob/main/Resources/tradable_cryptocurrencies_table.PNG"> 
</p>
The majority of cryptocurrencies are classified as #0 or #1.
BitTorrent is the sole cryptocurrency in class #2, as seen in the image above.

#### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply
<p align="center">
  <img src="https://github.com/NedaAJ/Cryptocurrencies/blob/main/Resources/bokeh_plot.png"> 
</p>
Directly plotting the scatter plot from two cryptocurrency features does not effectively separate the classes. When it comes to improved visuals, the PCA algorithm is the way to go.

## Summary
We classified 532 cryptocurrencies based on their similarity in attributes.
Each group's characteristics must be examined in order to establish its performance and prospective value to the investment bank's clients.

## Contact:
- Email : [neda.ahmadi.jesh@gmail.com](mailto:neda.ahmadi.jesh@gmail.com?subject=[GitHub]%20Source%20Han%20Sans)
- Linkedin: www.linkedin.com/in/neda-ahmadi-j

