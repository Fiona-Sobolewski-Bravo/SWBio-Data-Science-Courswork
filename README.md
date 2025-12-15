# SWBio-Data-Science-Coursework
# Project Overview
Using a Random Forest Model to classify drinking water samples as safe or not safe for consumption. 

# Dataset Description
⦁ **Source** - waterQuality1.csv <br>
⦁ **Entries** - 8,000 water sample observations <br>
⦁	**Features** - 20 water quality parameters (chemical and biological)<br>
⦁	**Classification**: <br>
&ensp;&ensp;&ensp;- is_safe = 1 -> water is **safe** to drink<br>
&ensp;&ensp;&ensp;- is_safe = 0 -> water is **unsafe** to drink <br>

**Note** - classes are imbalanced with a higher percentage of entries being classified as unsafe (0)

# Model Evaluation
Random Forest model was evaluated using:<br>
⦁	Accuracy value<br>
⦁	Precision, recall, and F1-score for each class<br>
⦁	Confusion matrix <br>

# Library Installation
This project was developed and run using **JupyterLab** and requires the following libraries: <br>
⦁	numpy<br>
⦁	pandas <br>
⦁	scipy <br>
⦁	seaborn <br>
⦁	scikit-learn<br>
⦁	matplotlib.pylab<br>
⦁	kagglehub<br>
⦁	os<br>

To run this project please ensure that all of the libraries listed above have been installed:

	pip install numpy pandas scipy scikit-learn matplotlib seaborn kagglehub
