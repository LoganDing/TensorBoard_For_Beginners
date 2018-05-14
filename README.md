# TensorBoard_Example

Example of how to use TensorBoard in TensorFlow 

# Setup

Either clone or download the repo then run the following command inside the directory where the project is located:

```
pip install requirements.txt
```

This will ensure that you have correct packages installed in order to run the notebook

***Note: If you do not have Jupyter installed, run the following command:***

```
pip install jupyter
````

# Running Notebook 

Once you have the appropriate packages installed, navigate to the project directory in two separate terminals and run the following commands:

```
#Terminal 1
jupyter notebook

#Terminal 2 
tensorboard --logdir="/tmp/kings_county"
```
