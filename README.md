## Skin Cancer Classification

<img width="774" alt="Screenshot 2024-07-04 at 5 35 48 PM" src="https://github.com/ihsiukaoBerkeley/Skin-Cancer-Classification/assets/117419224/d732fb8c-9295-4745-95d2-161877abdfd0">

### Members:
- Nathan Arias (nathanarias@berkeley.edu)
- Douglas Houghton (dchoughton@berkeley.edu)
- I-Hsiu Kao (ihsiukao@berkeley.edu)

### Dataset: https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000/data

### Dataset description:

Modified National Institute of Standards and Technology (MNIST) Human Against Machine (HAM) 10,000
Training of neural networks for automated diagnosis of pigmented skin lesions is hampered by the small size and lack of diversity of available dataset of dermatoscopic images. We tackle this problem by releasing the HAM10000 ("Human Against Machine with 10000 training images") dataset. We collected dermatoscopic images from different populations, acquired and stored by different modalities. The final dataset consists of 10015 dermatoscopic images which can serve as a training set for academic machine learning purposes. Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions: Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec), basal cell carcinoma (bcc), benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl), dermatofibroma (df), melanoma (mel), melanocytic nevi (nv) and vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc).
More than 50% of lesions are confirmed through histopathology (histo), the ground truth for the rest of the cases is either follow-up examination (follow_up), expert consensus (consensus), or confirmation by in-vivo confocal microscopy (confocal). The dataset includes lesions with multiple images, which can be tracked by the lesion_id-column within the HAM10000_metadata file.

### Hypothesis:

Machine learning models can be applied to a variety of dermatoscopic pigmented skin lesion images with sufficient accuracy to assist physicians in the diagnosis and confirmation of several important diagnostic categories.

### Directories:

working_code: non-final version codes

207_FinalProject_Arias-Houghton-Kao.pdf: presentation slides

Final_EDA.ipynb: final version of dataset EDA code

Final_metadata_model.ipynb: final version of metadata neural network model code

Final_test_hyperparam_w_clean_train.ipynb: final version of CNN model hyperparameter testing on clean training set code

Final_test_image_aug_w_oversampler.ipynb: final version of CNN model hyperparameter testing on oversampling set, image augmentation set, and oversampling + image augmentation set code

Final_test_mixed_model.ipynb: final version of mixed model (CNN + metadata model) hyperparameter testing on clean training set, oversampling set, image augmentation set, and oversampling + image augmentation set code

Final_test_mixed_model_binary.ipynb: final version of mixed model binary classification (CNN + metadata model) hyperparameter testing on clean training set, oversampling set, image augmentation set, and oversampling + image augmentation set code

CNN_hyperparam_test.xlsx: output from Final_test_hyperparam_w_clean_train.ipynb and Final_test_image_aug_w_oversampler.ipynb


mixed_model_hyperparam_test.xlsx: output from Final_test_mixed_model.ipynb
