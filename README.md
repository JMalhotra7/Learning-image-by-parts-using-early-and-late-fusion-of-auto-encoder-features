# Learning-image-by-parts-using-early-and-late-fusion-of-auto-encoder-features

### Description
A novel sub-part learning scheme is introduced in our work for the purpose of recognizing handwritten numeral images. The idea is borrowed from the concept of visual
perception and part-wise integration of visual information by the cortical regions of the brain. In this context, each numeral image is divided into four half-parts: top-half, bottomhalf, left-half and right-half; the other half of the image being kept masked. An efficient data representation is derived in an unsupervised manner, from each image part, using convolutional auto-encoders (CAE), for our learning scheme that involves both early and late fusion of features.

### Citation
If using this code, please cite our work using :

	Susan, S., Malhotra, J. Learning image by-parts using early and late fusion of auto-encoder features. Multimed Tools Appl (2021).
Link of the article: https://rdcu.be/cnHsd

### Usage
**Step 1: Preparing Patches (Top, Bottom, Left, Right).**<br />
Data Preparation.ipynb

**Step 2: Learning feature vector for all patches.**<br />
Top.ipynb, Bottom.ipynb, Left.ipynb, Right.ipynb 

**Step 3: Obtaining early fusion probabilties by giving combined feature vector to classifier.**<br /> 
Early fusion probabilities.ipynb

**Step 4: Obtaining probabilties score for each individual patch.** <br />
Late fusion feature.ipynb 

**Step 5: Fusing probabilties score obtained through early fusion and late fusion. Giving the fused vector to classifer to get the predicted class.** <br />
Late fusion feature.ipynb
