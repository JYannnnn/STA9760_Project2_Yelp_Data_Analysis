## STA9760 Project2: Analyzing 10Gb of Yelp Reviews Data

#### Goal: 
- Provision a Spark cluster on AWS EMR, connect it to a Jupyter Notebook and then run a series of queries (in python with DataFrame API or Spark SQL) that answer a few simple questions about the Yelp Data available.
- Download the Yelp data and then upload it back to an S3 bucket that is accessible via EMR.
- Analysis.ipynb file must demonstrate that the data is being read from S3.

#### Dataset: 
- https://www.kaggle.com/yelp-dataset/yelp-dataset#yelp_academic_dataset_user.json

#### Cluster Configuration：

<img width="1383" alt="cluster" src="https://user-images.githubusercontent.com/60801548/81031775-666fea00-8e5b-11ea-9b0a-5ec2a0764c51.png">

#### Notebook Configuration：

<img width="1432" alt="notebook" src="https://user-images.githubusercontent.com/60801548/81031822-98814c00-8e5b-11ea-93dd-2c7c0ab7869a.png">

#### S3 Hosted Files: Files are available for "public access"
- s3://sta9760-yelp-reviews-datasets/*yelp_academic_dataset_business.json
- s3://sta9760-yelp-reviews-datasets/*yelp_academic_dataset_review.json
- s3://sta9760-yelp-reviews-datasets/*yelp_academic_dataset_user.json
<img width="1352" alt="Screen Shot 2020-05-04 at 11 13 08 PM" src="https://user-images.githubusercontent.com/60801548/81032191-db8fef00-8e5c-11ea-8083-b8f7bfcbe9b0.png">
