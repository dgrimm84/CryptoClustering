# CryptoClustering - Module 19
The main file in this repository (Crypto_Clustering.ipynb) contains code that performs the following:
- imports crypto_market_data.csv from the Resources file and into a dataframe
- The dataframe is plotted to see the data we are working with:
  
  ![image](https://github.com/user-attachments/assets/8864481f-ca64-49be-9a48-422b0b28459c)

- a StandardScalar is called to transform the data into a scaled relationship for easy of processing

  ![image](https://github.com/user-attachments/assets/a7db5b1c-e130-4748-a973-9189134200e5)

- a KMeans fucntion is called using this data to plot an Elbow Curve to find the best value of k to be used in a scatter plot to represent this scaled data

  ![image](https://github.com/user-attachments/assets/f5662f2e-4f1a-4742-986d-fc00fd278e06)

  ![image](https://github.com/user-attachments/assets/d0067aff-c3c0-488f-b6ec-d3b0b0838890)

- A specified KMeans calculation is done with the number of clusters set to "4" as plotted above.  This resulting data is plotted through a predict, the predict values are added as a new column in the dataframe, an a scatter plot is created from this result

  ![image](https://github.com/user-attachments/assets/bbda2d3d-226b-410b-9d64-e910ce115409)

- this scaled data is then passed through a Principal Component Analysis (PCA) calculation to determine the explained variance ratio.  A new dataframe with these calculated values is created

  ![image](https://github.com/user-attachments/assets/f794f29e-ae4d-43a5-b860-d7368c073d3f)

- the same process as used above of finding what value of K will be best for this new PCA-calculated data is plotted on an elbow curve is performed

  ![image](https://github.com/user-attachments/assets/0de0fdfe-7da9-43aa-a67d-7d064e13d275)

  ![image](https://github.com/user-attachments/assets/ad0b6e13-c937-47c4-947e-06a7ea9e90bb)

- Since "4" is the preferred number of clusters for this PCA data as well, a new KMeans calculation is performed, the pca_class column is added to each row in the dataframe, and a scatter plot is generated from this new data

  ![image](https://github.com/user-attachments/assets/7e0d01df-81bc-4509-8aaf-50a32eb9c9f2)

- The two elbow curves are plotted together to view them at the same time and compare them

  ![image](https://github.com/user-attachments/assets/ac1741fb-3a07-4c07-9be6-03cff8c14dfe)

- In the same manner, the two scatter plots are plotted togehter so they can be seen side by side for analysis

  ![image](https://github.com/user-attachments/assets/0fb6d106-777b-4959-99de-2d5f40342066)

  ![image](https://github.com/user-attachments/assets/3a661250-bc70-47ef-b846-577355130f1e)




  
