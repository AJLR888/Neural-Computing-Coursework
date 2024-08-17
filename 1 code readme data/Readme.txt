++++++++++++++ Comparison between Multilayer Perceptron (MLP) and Support Vector Machine (SVM) models on sentiment analysis of the IMDb Movies Reviews Data Set +++++++++++++++++

IMPORTANT:

* Make sure the CSV file is in the working directory of Python. You can use the following code to check so:
import os
cwd = os.getcwd()

Source: https://stackoverflow.com/questions/5137497/find-the-current-directory-and-files-directory



Requirements:

Python: 3.8.18
Jupiter Notebook 6.4.8.
Pandas version: 1.4.2
NLTK version: 3.8.1
PyTorch version: 2.2.0
NumPy version: 1.24.3
Matplotlib version: 3.8.0
Seaborn version: 0.13.0
Scikit-learn version: 1.3.0
BeautifulSoup (bs4) version: 4.12.2


Setup instructions:
1. Extract all the files from the zip file
2. Change directory (cd) to the extracted folder, and save any test data into this root folder
3. Create a new virtual environment and install packages from requirements:
	3.1 virtualenv AJLR_env
	3.2 cd AJLR_env
	3.3 source bin/activate
	3.4 cd -
	3.5 pip install -r requirements.txt
4. Copy and paste the following code in the working directory to open the IPYNB:
	4.1 IMDB.CSV
	4.2 MLP_IMDb.ipynb
	4.3 SVM_IMDb.ipynb



Extra Notes: 
* Note that the SVM model takes around 40 min to run, whereas MLP takes over 2 hours to run (core i5 10th GEN, 16Gb Ram)

* The work was created using Anaconda environment Version 2.5.2