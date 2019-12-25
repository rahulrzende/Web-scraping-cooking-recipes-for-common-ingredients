# Web-scraping-cooking-recipes-for-common-ingredients

In this assignment, you will gain hands-on practice in scraping data. You will be required to scrape at least 100 recipes from the web, provide their ingredient lists and clean the ingredient data for the further calculation.

You will have three main tasks in this part:

scraping data: scrape at least 100 recipes from the website that you choose
cleaning data: clean your ingredient data for further calculation. This includes, but is not limited to, removing excess white spaces, correcting for all edge cases, and correcting any remaining formatting issues
calculating: what are the 10 most common ingredients used in these recipes? 
Submission Details for Part 2:
You will submit three data files all in .csv format, named a2_rawData.csv, a2_cleanData.csv and a2_results.csv:

Data for the rawData and cleanData files should be formatted with three columns: url, name, ingredient - in that order, all lowercase. Each ingredient should be listed on a separate line. Note that this will likely result in repeating entries for name and url.
url: should contain the link where the recipe can be found
name: the name of the recipe
ingredient: the name of the ingredient
Data for the calculation result should contain three columns: word, count, proportion - in that order, all lowercase. The list of ingredients should be sorted such that the most common ingredient is listed first and 10th most common is listed last.
ingredient: the ingredient name
count: the number of times the ingredient appears in your list
proportion: the proportion of recipes in which the ingredient appears
There are examples of the three required data files above: example_rawData.csvPreview the document, example_cleanData.csvPreview the document, example_results.csvPreview the document.

If you use the Jupyter Notebook, you only need to submit one file named a2.ipynb. You should outline the notebook in three sections (i.e. scraping data, cleaning dta and calculating) and use Markdown cells to make titles for each section. Please clear all the outputs before you submit the file.

If you are not use the Jupyter Notebook (i.e. just Python), you will write the scripts in .py file. In this case, you should submit three .py files: a2_collect.py, a2_clean.py and a2_calculate.py. Each script performs only one task.

Your script(s) should only generate three data files as outlined below. No other print outputs regardless of the coding environment you use. 
