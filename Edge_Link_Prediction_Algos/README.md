# Prerequisite
* python3
* pandas
* numpy
* sklearn
* networkx
* jupyter-notebook

# Data Preprocessing
* Run following script before running the Jupyter notebook
	* source data-processing.sh
* The script creates otc.csv which will be further processed on in the jupyter notebook code 

# Running source code
* Open the Link_prediction_Final.ipynb notebook in jupyter and execute cell by cell to verify the results

* credits:
	* 1) The algorithm for fairness-goodness is used as it is from here. It is based on the paper [1]. 
	* 2) The bias and deserve algorithm was implemented by us, referring paper[2].

# Modules
* The above code is made modular and can be ran individually as well
* You can find the notebooks for the same under Modules/

# Evaluation result
* This is a text file that consists of manual evaluation to identify the following findings
	* For algorithm fairness-goodness, it was observed that for ratings greater than 0.3 avg fairness(node1) and goodness(node2) gives better result as compared to product of the same.
* For more details on fairness and goodness, I really encourage to read and understand the paper[1].
* All the references and related papers gives a good understanding about edge link prediction in graphs

# Reference
* [1] Kumar, S., Spezzano, F., Subrahmanian, V., & Faloutsos, C. (2016). Edge Weight Prediction in Weighted Signed Networks. Data Mining (ICDM), 2016 IEEE 16th International Conference on, 221-230.

* [2] b. Mishra, A., & Bhattacharya, A. (2011). Finding the bias and prestige of nodes in networks based on trust scores. Proceedings of the 20th International Conference on World Wide Web, 567-576. 

**NOTE: Some resuts may not be in compliance with the Report since they were ran at different iterations. Detailed messages are provided in the notebook that would make it more clear.**
