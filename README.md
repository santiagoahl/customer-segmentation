<h1 align="center">
  <br>

  <br>
  Costumer Segmentation
  <br>
</h1>

<h4 align="center">Unsupervised Learning DBSCAN Model to group costumer personality from its data. 
</h4>

<p align="center">
  <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a> <a href='https://github.com/shivamkapasia0' target="_blank"><img alt='scikit-learn' src='https://img.shields.io/badge/scikit-learn-100000?style=for-the-badge&logo=scikit-learn&logoColor=FFFFFF&labelColor=FF6A00&color=1882EA'/></a> <a href='https://numpy.org/' target="_blank"><img alt='numpy' src='https://img.shields.io/badge/Numpy-100000?style=for-the-badge&logo=numpy&logoColor=0250BD&labelColor=8BBFEA&color=B1DCFF'/></a>  <a href='https://pandas.pydata.org/' target="_blank"><img alt='pandas' src='https://img.shields.io/badge/pandas-100000?style=for-the-badge&logo=pandas&logoColor=2D0090&labelColor=9D7BEA&color=D2C0FA'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a> 
</p>

![screenshot](https://img.freepik.com/premium-vector/customer-segmentation-target-audience-analysis-vector-isometric-illustration-audience-segmentation-i_103044-1952.jpg?w=2000)

## Key Features

This machine learning model clusters the world contries according with econ and social data. This prediction is one of 4 clusters. The dataset is taken from the [Customer Personality Analysis Kaggle Competition](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis). So here are the key features of this project:

* Prediction is based on these costumers' attributes

People
	* `ID`: Customer's unique identifier
	
	* `Year_Birth`: Customer's birth year
	
	* `Education`: Customer's education level
	
	* `Marital_Status`: Customer's marital status
	
	* `Income`: Customer's yearly household income
	
	
	* `Kidhome`: Number of children in customer's household
	
	* `Teenhome`: Number of teenagers in customer's household
	
	* `Dt_Customer`: Date of customer's enrollment with the company
	
	* `Recency`: Number of days since customer's last purchase
	
	* `Complain`: 1 if the customer complained in the last 2 years, 0 otherwise

Product
	* `MntWines`: Amount spent on wine in last 2 years
	
	* `MntFruits`: Amount spent on fruits in last 2 years
	
	* `MntMeatProducts`: Amount spent on meat in last 2 years
	
	* `MntFishProducts`: Amount spent on fish in last 2 years
	
	* `MntSweetProducts`: Amount spent on sweets in last 2 years
	
	* `MntGoldProds`: Amount spent on gold in last 2 years
	
	* `Promotion`
Place
	* `NumDealsPurchases`: Number of purchases made with a discount
	
	* `AcceptedCmp1`: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
	
	* `AcceptedCmp2`: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
	
	* `AcceptedCmp3`: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
	
	* `AcceptedCmp4`: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
	
	* `AcceptedCmp5`: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
	
	* `Response`: 1 if customer accepted the offer in the last campaign, 0 otherwise

	* `NumWebPurchases`: Number of purchases made through the company’s website
	
	* `NumCatalogPurchases`: Number of purchases made using a catalogue
	
	* `NumStorePurchases`: Number of purchases made directly in stores
	
	* `NumWebVisitsMonth`: Number of visits to company’s website in the last 

* Dimensionality reduction with **PCA**.
* Based on **Scikit-Learn** modules and functions such like:
  - `decomposition.PCA`: Dimensionality reduction.
  -  `cluster.DBSCAN` 
  -  `cluster.KMeans` 
  -  `cluster.AgglomerativeClustering` :   Hierarchical Clustering.
  - `metrics.silhouette_score` :   Main clustering score.

## How To Use

To clone and run this application, follow these steps

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/costumer-segmentation.git

# Go into the repository
$ cd ostumer-segmentation

```

## Credits
This software uses the following open libraries and datasets:


- [Numpy](http://electron.atom.io/)
- [Matplotlib](https://nodejs.org/)
- [Seaborn](https://github.com/chjj/marked)
- [Pandas](http://showdownjs.github.io/showdown/)
- [Sci-kit Learn](http://codemirror.net/)
- [Dataset](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data?resource=download)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
