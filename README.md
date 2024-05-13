Salient points of the code:
1. To develop a CNN for classifying the severity of Diabetic Retinopathy from an index of 0 (no DR) to 1-3 (non-proliferative) to 4 (proliferative) using
   images from a Kaggle dataset.
2. Used standard preprocessing layers from Keras and ResNet50 as the pre-trained model with 7 layers as fine-tuned. Attempted analysing the model by drawing disease
   conditions on 0 severity (no DR) images, and then using the model to get their new severity classification.
3. Obtained a model stuck to 0 because of the highly unbalanced dataset (>70% had class label 0). Even using class weights to counter this did
   not solve this problem.

"ResNet50_64X64.ipynb" shows the results of the model training on images with 64X64 pixels. Similarly, "ResNet50_128X128.ipynb" is for 128X128 pixels.
The "work_summary_ppt.pdf" is the presentation our group used to present the work and the code. 
