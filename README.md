This is a project where different misc topics are explored.

Few points worth mentioning regarding directory structure:
--csv is placed under data/raw/
--Processed csv is places under data/processed after computation
--Test predictions are available under data/submitted
--Notebook is present in notebooks folder
--misc is a package which load all initial packages(__init__.py) and sets data file paths under config.py
  ++ Abstracts the messy paths in the main notebook to here, so that cleaner view can be provided
--scripts folder is a placeholder for future purposes

--How to run this?
  ++ start Anaconda prompt and go to this folder's parent locationr and type jupyter notebook
  ++ notebook starts with the parent folder as the base location and you can navigate to different projects from there



---------------------------------------------------
Files
--------------------------------------------------
linear_regr_diabetes.ipynb - using diabetes dataset, predict the disease progression one year after the baseline

linear_regr_house_sales.ipynb - Basic exercise for linear regression model, exploring RMSE, MAPE metrics 

regr_feature_Selection.ipynb - Basic feature selection techniques

classification_eval.ipynb - classfication evaluation metrics.

