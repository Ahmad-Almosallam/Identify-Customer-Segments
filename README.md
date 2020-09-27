# Identify Customer Segments

This project about identify customer segments, I used K-means unsupervised learning algorithm and Principal Component Analysis(PCA) to dimensionality reduction
In this project we have two dataset the first one is general dataset for people of Germany and the second for customers of a mail-order sales company.

Steps of the project as follows:
- Load The data
- Preprocessing (Data Cleaning & engineering)
- Feature Transformation (feature scaling and perform the PCA)
- Interpret Principal Components
- Clustering
- Compare Customer Data to Demographics Data

## Result
Cluster 3 is overrepresented in the customer data compare to the general data.
- ANREDE_KZ(Gender:Male) = 0.877131
- SEMIO_VERT(Personality typology:dreamful) = 7.023095
- SEMIO_SOZ(Personality typology:socially-minded) = 5.361885
- FINANZ_VORSORGER(Financial typology:very low) = 4.899584
- SEMIO_FAM(Personality typology:family-minded)= 4.714035
- HH_EINKOMMEN_SCORE(Estimated household net income:highest income) = 1.024195
- ALTERSKATEGORIE_GROB(Age:46 - 60 years old) = 3.723633
So, I can say that the customer is often male and its age around 46 to 60 years old and has highest income and his personality not dreamful,socially-minded,family-minded and for Financial not prepared(very low)

Cluster 2 is underrepresented in the customer data compare to the general data.

- ANREDE_KZ(Gender:Female) = 1.766711
- SEMIO_VERT(Personality typology:dreamful) = 3.381906
- SEMIO_SOZ(Personality typology:socially-minded) = 3.560164
- FINANZ_VORSORGER(Financial typology:very low) = 3.786574
- SEMIO_FAM(Personality typology:family-minded)= 3.720582
- HH_EINKOMMEN_SCORE(Estimated household net income:average income) = 4.462347
- ALTERSKATEGORIE_GROB(Age:30 - 45 years old) = 2.760763

So, I can say that the customer is often female and its age around 30 - 45 years old and has average income and his personality very dreamful,socially-minded,family-minded and for Financial average prepared
