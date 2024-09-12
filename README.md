# Unsupervised Learning
## Project: Creating Customer Segments

**Project Overview**
This project aims to segment customers based on various behavioral and demographic data points. The goal is to better understand customer groups to tailor marketing strategies and enhance customer service.

**ML Algorithms and Statistical Methods Used**
* K-Means Clustering: Used to segment customers into distinct groups based on similarities within each cluster and differences across clusters.
* Principal Component Analysis (PCA): Applied to reduce dimensionality while retaining the most significant variation in the data, aiding in better visualization and efficiency in clustering.
* Silhouette Score: Employed to determine the optimal number of clusters by assessing how similar an object is to its cluster compared to other clusters.

**Visualization Techniques**
* Scatter Matrix: Visualizations such as scatter matrices have been used to explore the relationships and distributions of the data features.
* Cluster Visualization: After applying PCA, cluster assignments are visualized in a 2D space to interpret how customers are grouped together.

**Business Impact**
* Improved Targeting: By understanding distinct customer segments, the company can tailor marketing efforts to match the specific needs and preferences of each group, potentially increasing conversion rates.
* Resource Allocation: More efficient use of resources by focusing efforts where they are likely to have the most impact based on the segmented customer data.
* Customer Retention: By addressing the specific needs of each segment, the company may improve customer satisfaction and retention rates.

**Strategic Recommendations**
* Tailored Marketing Campaigns: The analysis likely suggests developing customized marketing campaigns for each customer segment to address their unique characteristics and preferences.
* Continuous Improvement: It's recommended to periodically reevaluate the segmentation to keep up with changing customer behaviors and market conditions.
* Predictive Analytics: Utilize the segmentation model to predict future buying behaviors and preferences, which can inform product development and promotional strategies.
### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer. 

### Code

Template code is provided in the `customer_segments.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `customers.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `customer_segments/` (that contains this README) and run one of the following commands:

```bash
ipython notebook customer_segments.ipynb
```  
or
```bash
jupyter notebook customer_segments.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Note (m.u.) is shorthand for *monetary units*.

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous); 
2) `Milk`: annual spending (m.u.) on milk products (Continuous); 
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous); 
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal) 


