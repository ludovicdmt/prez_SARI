# Présentation pour SARI le 2019/06/06

## Sujets introduits
* Utilisation de [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/)
* Le [notebook](https://github.com/ludovicdmt/prez_SARI/blob/master/keras_CNN_concat.ipynb) de présentation en français utilisant [Keras](https://keras.io/) ([TensorFlow](https://www.tensorflow.org/) backend)
* Exemple de [TensorBoard](https://www.tensorflow.org/guide/summaries_and_tensorboard)
* Les poids d'un réseau CNN + une RegLog entraînés ([```weights/```](https://github.com/ludovicdmt/prez_SARI/tree/master/weights))
* Un début de micro-API avec [Flask](http://flask.pocoo.org/) pour servir le modèle ([```api/```](https://github.com/ludovicdmt/prez_SARI/tree/master/api))

## Kaggle Leaf Classification
* [Concours](https://www.kaggle.com/c/leaf-classification) Kaggle pour télécharger les données
* [Kernel](https://www.kaggle.com/abhmul/keras-convnet-lb-0-0052-w-visualization) original dont provient la plupart du code

## Quelques resources
* [Introduction](https://bit.ly/315tIID) aux réseaux de neurones
* [Tutos](https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html) d'introduction à Keras
* [Tuto](https://towardsdatascience.com/deploying-keras-deep-learning-models-with-flask-5da4181436a2) d'introduction à Flask

## Reveal.js slides 
Il faut d'abord cloner reveal.js :  
```
git clone https://github.com/hakimel/reveal.js.git  
cd reveal.js  
git checkout 3.5.0  
cd ..  
```
Puis :
``` 
jupyter nbconvert keras_CNN_concat.ipynb --to slides --reveal-prefix reveal.js
```  
## Packages utilisés
* JupyterLab
* Keras
* Tensorflow
* Scikit-learn
* Seaborn
* OpenCV  
* Pandas  

Ils peuvent être installés avec pip :  
```
pip install -r requirements.txt
```

