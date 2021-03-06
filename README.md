## Project Description :
Predict sale amount based on daily sale volume.

training-data : **train.csv**

test-data : **output.csv**

<img width="100" alt="image1" src="https://user-images.githubusercontent.com/74386667/119402687-87b7a880-bcf2-11eb-9d2c-d2af24b4d9a1.png">

#### Preprocessing Steps :

* Analyze date with `jdatetime` and extract new features 
* Normalize data by `sklearn.preprocessing.Normalizer`
* Drop uncorrelated features

#### Score Function :

<img width="509" alt="image" src="https://user-images.githubusercontent.com/74386667/119407227-319a3380-bcf9-11eb-92e3-305536b3e9a8.png">

#### Different Models' Smape-Score :

<img width="1000" alt="image3" src="https://github.com/mohannatd/---/blob/main/models_score.png?raw=true">

## Requirements :

`jdatetime`

`pandas`

`numpy`

`sklearn`

`matplotlib`

`seaborn`

## Google Colab link:

*https://colab.research.google.com/drive/1Z2fwA7yk4btmcE38Gi5hfOA4x4XdALgI?usp=sharing*

