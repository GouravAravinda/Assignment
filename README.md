# Assignment
E-commerce website that can be deployed on Kubernetes with a HTML,Javascript,CSS frontend and Flask for backend. 
The data ingestion API that is created will be capable of taking in data from the merchandiser and adding it to the 
database after it has been validated

## How to run data ingestion API

DataIngestion folder consists of the data ingestion API, which will be run using curl commands. The below curl commamnds have to be run when inside DataIngestion folder. 

curl 127.0.0.1:6000/category -d @category.json -H 'Content-Type:application/json
curl 127.0.0.1:6000/products -d @out.json -H 'Content-Type:application/json'


## How to run website
This would be run on docker using **docker-compose up -d --build** while inside the project directory. The frontend will be running on port 6000. 


## Screenshots of Application

![HomePage - Displaying Trending Products](Project/Documentation/ProductPageTrending.jpg)
![HomePage - Displaying Searched Products](Project/Documentation/ProductPageSearch.jpg)
![HomePage - Displaying Prducts With Filter Applied](Project/Documentation/ProductPageWithFilterApplied.jpg)
![HomePage - Displaying Products With Category Applied](Project/Documentation/ProductPageCategory.jpg)
![ProductDetailPage - Displaying details of products](Project/Documetation/ProductDetailPage.jpg)
