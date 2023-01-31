# Portfolio_DataScience SQL
Here are various projects that I have developed involving managing of SQL databases.

* We have "SQL_project.ipynb". The project's main objective was to knwo how to connect and interact
  with an SQL database using python. The data corresponds to a bank's marketing campaign results.
  Here demographic and financial values are substracted from a group of people, along with whether
  the marketing campaign was successful or not.
  
  This project first shows how to create a PostgreSQL database using python code. After that, a CSV
  is converted to a suitable format that could be translated to the aformetioned platform. Then, some
  questions were stated to solve using this information; this ranged from simple questions using basic
  SQL commands to retrive basic statistic values of the to the use of classification algorithms to
  predict whether the marketing campaign would be successful in certain profiles of people.
  
  For this last part, an Exploratory Data Analysis was carried out to evaluate whether certain factors
  could affect the success of this campaign: existence of loan, existence of deposits and their balance.
  After this, the data was cleaned: elimination of outliers, creation of dummy variables, amongst other
  procedures; so that data classification algorithms could be performed. Supervised learning algorithms 
  were used for this: logistic regression, k-nearest neighbour and decision tree. Each one yielded
  different results (decision tree being the most accurate one) and different conclusions were drawn from
  all this methods, the most important being that there was a correlation between the factors metioned above
  and the success of the bank's marketing campaign.
