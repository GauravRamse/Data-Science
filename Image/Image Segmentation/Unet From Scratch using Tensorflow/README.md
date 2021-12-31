
### Image segmentation from Scratch using Tensorflow

I have used dataset from Kaggle competition [Kaggle](https://www.kaggle.com/c/data-science-bowl-2018)


Things learned.
1) In tensorflow try to use tf.Data.dataset object, because we can exploit prefetch from tensorflow, Which will decrease the time required for loading of images.
2) In tensorflow we can use GradientTape for custom loop and exploit more functionalities that we can not use using model.fit.

Future Implementation:
1) We have just created baseline model, where we use binary croessentropy as a loss function, But we will use IoU and dice coefitient next version of this implementation
