# ABC News Topic Modelling

This project analysed the top topics of news headlines in Australia. Each of the news headline will be analysed using NMF topic modelling algorithm to cluster the keywords. The cluster of keywords will be used to derive the topic title. Each words in the news headline are tokkenize and lemmatized. 

From the analysis of topic frequency, this report found that Australia top three news topics are government policies, sports and accidents. Australians were interested in the news which may affect their daily lives such as new rules from its government.


# Some of the Libraries used in this project:
   - NLTK (Natural Language Toolkit)
   - NMF (Non-negative Matrix Factorization)
   - Pandas
   - Matplotlib
   - Numpy 


# Local Setup
Jupyter notebook is required to run the code.

If the Jupyter notebook is in the local computer:
1. Copy this folder to your jupyter notebook path. 
2. Unzip the `abcnewsweb` folder inside the `./data/abc` folder. The file is compressed due to its large size.
3. Move `abcnewsweb` csv file from the unzip folder to the `./data/abc` main folder.
3. Open the `ABCNewsTextAnalysis.ipynb` file in your local jupyter notebook. 
4. Run the code in the jupyter notebook.