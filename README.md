### 1.1 Intro
This project was done for the course Intro To ML at the University of Zurich. 

### 1.2 Data Source/Set
The data for this group project is taken from OpenML’s free datasets and can be accessed through OLAT. The following link provides further description of the data: https://www.openml.org/search?type=data&sort=runs&id=42165&status=active Note that the original response variable is numeric and used in regression task settings. However, for the purpose of this seminar the response variable SalePrice was transferred into price-range bins/classes called Class.

### 1.3 Task: Real Estate Price Class Estimation
The data set provides 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. Students are to use the given data to train a model that is able to produce price bin/class estimations. The response classes1 are:

0. Sale Price between $0 and $100,000 
1. Sale Price larger than $100,000 but smaller than or equal to $200,000 
2. Sale Price larger than $200,000 but smaller than or equal to $300,000 
3. Sale Price larger than $300,000 but smaller than or equal to $400,000 
4. Sale Price larger than $400,000 

This tasks implies dealing with the following questions: 
- How does one handle missing data and outliers? 
- Selection of relevant explanatory variables (features) for your model: Does a model that includes all available 79 features yield the best results or is a restricted model with only a subset more convincing?
- Feature engineering: Does adding other or creating new features (besides the given fundamental data) improve your model (e.g. macroeconomic or demographic data etc.)?
- Class imbalance: Is class imbalance affecting accuracy?
