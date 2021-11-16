## The Great Divide: Factors associated with low COVID-19 vaccination rates in the US 

- Modeled county-level COVID-19 vaccination rates using linear regression (OLS, interaction & polynomial terms, regularization with Lasso & Ridge)  
- Obtained data by web scraping the CDC website with Selenium and BeautifulSoup
- Used regression coefficients to determine which political and socioeconomic factors have the greatest effect on COVID-19 vaccination rates at the county level
  - As demonstrated below, the feature with the greatest effect is the % vote split in the 2020 presidential election (% vote for GOP candidate - % vote for Democratic candidate), indicating that red counties have lower vaccination rates than blue counties

<img width="783" alt="image" src="https://user-images.githubusercontent.com/79233614/141700055-f602ac76-6e8b-4c99-a7bb-fbf1cec2c1fe.png">

For additional figures, check out this project's [presentation slides](https://github.com/mayaremington/regression-covid-vax/blob/main/%20covid_vax_regression.pdf)!

**Jupyter notebooks:**  
[1) Webscraping](1_covid_vax_webscraping.ipynb)  
[2) Cleaning](2_covid_vax_cleaning.ipynb)  
[3) Modeling](3_covid_vax_regression.ipynb)  

