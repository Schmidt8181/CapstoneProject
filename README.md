Exploring US Wages and Occupations

#Project Description:

This notebook explores US wages by Occupation and tests the question “can you accurately predict an employment category using wage, gender, share of females in field, if field is male dominated, and if field has a significant wage gap?


#Data Description:

The dataset used was gathered from https://www.kaggle.com/jonavery/incomes-by-career-and-gender. From the Kaggle page, "This dataset, retrieved from the Bureau of Labor Statistics, shows the median weekly incomes for 535 different occupations. The data encompasses information for all working American citizens as of January 2015. The incomes are broken into male and female statistics, preceded by the total median income when including both genders. The data has been re-formatted from the original PDF-friendly arrangement to make it easier to clean and analyze." There were a number of rows with missing information for mens and womens weekly wages. Those rows were removed because it would be inappropriate to extrapolate income numbers across occupations.

#Results:

Random chance gives each of our 11 labels an equally likely 9% chance if we just guess. The best performing estimator was right 39% of the time. These findings support the idea that there is some substructure to the occupation labels and wages and gender have an influence on that.  


#Next Steps:
 
 For the next steps, I would like to go back and attempt to predict wages, using this same dataset. I am very curious what occupations did NOT have wage information and what sort of information I could still learn, even without wage data for those occupations. I would also like to dig in more, and see if I can discern what caused management to be mislabeled as healthcare so often. I would also like to investigate the feature importance for the best performing model.
