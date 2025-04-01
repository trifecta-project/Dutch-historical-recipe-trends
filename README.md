# Dutch-historical-recipe-trends

This is the repository for the paper *Detecting Changing Culinary Trends Through Historical Recipes* by Gauri Bhagwat, Marieke van Erp, Teresa Paccosi, and Rik Hoekstra (currently under review).

This repository contains a **cleaned corpus** and a series of Jupyter notebooks used to analyze and process historical recipe data. 

**Corpus**

This folder contains all the cookbooks used to extract recipes and ingredients and a csv with newspaper data created in *van Erp, M., Wevers, M., & Huurdeman, H. (2018). Constructing a recipe web from historical newspapers. In The Semantic Web–ISWC 2018: 17th International Semantic Web Conference, Monterey, CA, USA, October 8–12, 2018, Proceedings, Part I 17 (pp. 217-232). Springer International Publishing*.

**Code**

The notebooks are structured in a way that allows for step-by-step execution and analysis, starting from the extraction of recipe data to the analysis.
The code is divided in 3 parts and is available in the following files. They are arranged in the order they should be executed:

_Data Preprocessing_

⚙️ The first notebooks are respectively used to process and extract recipes (`1_recipe_extraction`) and ingredients (`2_ingredient_extraction.ipynb`) from cookbooks and from newspapers (`3_historical_recipe_web.ipynb`), while `4_relative_frequency.ipynb` is used to calculate the relative frequency of ingredients. 

_Analysis_

📊 The second set of notebooks is used for the analyses we proposed in the paper. `5_ingredient_usage_pattern.ipynb` looks at the most frequently shared ingredients across the different datasets and their evolution in terms of frequency over time. `6_recipe_complexity.ipynb` looks at the recipe complexity according to the average number of ingredients employed, while `7_seasonal_usage_patterns.ipynb` analyses the use of seasonal ingredients in newspaper recipes. 

_Pearson correlation for average frequency over time_ 

📈 In `8_stat_significance_mean.ipynb`, we provide a calculation of the Pearson correlation for ingredients' average frequency and time, as well as visualisations for average distribution, standard deviation and confidence interval.


Funded by the European Union under grant agreement 101088548 - TRIFECTA. Views and opinions expressed are however those of the author only and do not necessarily reflect those of the European Union or the European Research Council. Neither the European Union nor the granting authority can be held responsible for them.
