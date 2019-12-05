# ShipsDetection Exploring neural network architectures for locating ships in images
### Executable Files
For a quick demo, run the Jupyter Notebook `Demo.ipynb`.  
For a full training on the dataset, run the Jupyter Notebook `train.ipynb`.

### Requirements
The dataset can be downloaded on the kaggle competition website[1].  
In the notebooks, the following locations are referenced.  
Adapt the code or make sure to recreate the data structure:  
csv data for labels: `/datasets/ee285f-public/airbus_ship_detection/`  
training data: `/datasets/ee285f-public/airbus_ship_detection/train_v2/`  
test data: `/datasets/ee285f-public/airbus_ship_detection/test_v2/`  

To run the notebook, you need the following packages installed:
- tensorflow
- keras
- matplotlib
- pandas
- scikit.image
- scikit.learn

### ECE 285 Group Project Members
Jiacheng Hu
University of California San Diego  
jih135@ucsd.edu  
A91013815 

Kai Ye
University of California San Diego   
k1ye@eng.ucsd.edu  
A53309088 

Pu Cheng  
University of California San Diego    
pucheng@eng.ucsd.edu
A53306940

Zhenyan Wang  
University of California San Diego  
zhw028@ucsd.edu 
A53300836

### References
[1] - https://www.kaggle.com/c/airbus-ship-detection
