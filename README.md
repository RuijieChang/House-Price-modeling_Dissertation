# House-Price-modeling_Dissertation
## Introduction   
House is the necessity for most of the people, and it is the main component of wealth for most of the families in this world. As one of the most developed countries, there is no other real estate market is as large, transparent, and liquid as the US market. The scope of this research focus on the house price prediction in the region of California, US. In this project, the prediction of the house price is based on its images, numerical variables, and categorical variables. Moreover, based on the data collected from web scraping, it contains the exterior images of the house paring with the house price in the region of CA, US in 2020. 
A variety of factors will cause a tremendous difference in housing price, including exterior and interior of the houses. Multiple aspects containing exterior, and interior of the houses are taking into consideration in this dissertation. For instance, exterior house images, various eigenvalue of interior of house, and house location. overall, in this research, deep learning techniques are used to forecast the housing price in the region of CA, US based on feature fusion of multiple input (images and numerical variables). Based on deep learning method, Convolutional Neural Networks (CNN) is utilized to predict the housing price. We propose three models based on CNN method, image recognition and numerical input model, and a hybrid model with feature fused. First, we extract image features from pre-trained images dataset, training the model based on CNN method. Secondly, we added numerical features, including the number of bedrooms, the number of bathrooms, and the area, training the numerical feature separately to predict the housing price. Thirdly, we connect these two modules together to perform a hybrid house price prediction model with visual image and numerical features. As the result, the performances of three models are recorded to compare which model perform better in predicting the housing price. 

# Data description 
The dataset is comprised of both image data and numerical data, which is retrieved from an open-sourced website: Kaggle. ( https://www.kaggle.com/datasets/ted8080/house-prices-and-images-socal). The numerical data is in csv format, containing 7 columns and 15474 rows, which record the information of the address, number of beds, number of baths etc. of the houses. The image data is the picture of house, and it is in jpg format. Every house has the price and corresponding image. 
Columns of the textual file 
1.	image_id: the id of the image corresponds the houses.
2.	street: the street address of the house.
3.	citi: the city where the house is located.
4.	n_citi: the label encodes of the city column.
5.	bed: numbers of beds.
6.	bath: numbers of baths.
7.	sqft: square feet of the houses.
8.	price: the price of the house.
