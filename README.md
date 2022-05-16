## Exercise with the Movielens Dataset


#### Installation

To install the required dependencies, we recommend you to install Anaconda and run the following line:
```
conda env create -f conda_requirements.txt
```
This will create a conda environment which you can activate by running
```
conda activate breinstein
```

###### Manual Installation

This environment can also be created by following the following lines:
```
conda create -n breinstein python=3.7
conda activate breinstein
conda install numpy
conda install pandas
conda install seaborn
conda install collections
conda install surprise
conda install -c anaconda scikit-learn
conda install -c conda-forge jupyterlab
conda install -c conda-forge matplotlib
```
After this is performed please activate your environment as previously explained.


###### Using an already installed python / jupyter distribution

If you already use Python, please make sure the following packages are installed:
```
numpy
pandas
scikit-learn
jupyterlab (or jupyter notebook)
seaborn
matplotlib
collections
surprise

```
This can be done by simply running
```
pip install package_name
```

#### Running the files

Once you activate your environment, you can run on the terminal
```
jupyter notebook (or jupyter lab).
```
This will open an screen in which you can see the `DataMining_Practical_Recommender.ipynb` file. This is the main file we will use in the workshop. 