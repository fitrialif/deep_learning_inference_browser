# deep_learning_inference_browser
Example how to train a deep learning keras model to segment a tumor on brain MR and how to do deep learning inference in the browser


## Workflow

###Step 1: Train a keras model
###Step 2: Run inference in browser


## Code Requirements

###Step 1: Train a keras model

1. [Keras](https://keras.io/) and all its dependences. [See installation instructions](https://keras.io/#installation)

###Step 2: Run Inference in browser 

1. [encoder.py](https://github.com/transcranial/keras-js/blob/master/encoder.py) from [keras.js](https://github.com/transcranial/keras-js)

2. [keras.js](https://github.com/transcranial/keras-js) and its dependences. Instructions are provided [here](dependences_kerasjs.md) 

3. browserify to bundle the js files
```sh
npm install -g browserify
```

## Data Requirements

Step 1: [Brats data](https://sites.google.com/site/braintumorsegmentation/home/brats_2016) 2016 - segmentation of tumor subregions 

Step 2: Test images


### Usage

Uses browserify to create bundle js: 

```
browserify prostate-segmentation.js > ../dist/prostate-segmentation.js
```
