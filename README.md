# SparkML_OS_Project
Spark ML Tutorial and Examples for Beginners


## 🛠 Installation & Set Up

1. Use Docker Images : https://hub.docker.com/r/jupyter/pyspark-notebook/ (Need to install [docker](https://docs.docker.com/get-docker/) first) 

   ```sh
   docker pull jupyter/pyspark-notebook
   ```

2. Clone the repo
    ```sh
   git clone https://github.com/AnishEllore/SparkML_OS_Project.git
   ```
3. Go to the folder and run below command to setup jupyter notebook
   ```sh
   docker run -it --rm -p 8888:8888 --name jupyter -v /"${PWD}":/home/jovyan jupyter/pyspark-notebook start-notebook.sh
   ```
4. Open the Jupyter notebook in chrome and run mnist_analysis.ipynb

## Dataset
- MNIST: https://www.kaggle.com/oddrationale/mnist-in-csv
- Kaggle Titanic Dataset: https://www.kaggle.com/c/titanic/data
- MovieLens Dataset: https://grouplens.org/datasets/movielens/100k/
- Last.fm Music Dataset: http://www.dtic.upf.edu/~ocelma/MusicRecommendationDataset/lastfm-1K.html
- KDD Cup 1999 Dataset: http://www.kdd.org/kdd-cup/view/kdd-cup-1999/Data
