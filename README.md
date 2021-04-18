# Dogs_Classifier_CNN

The second project of my [Deep Learning](https://www.udacity.com/course/deep-learning-nanodegree--nd101) Nanodegree from [Udacity](https://www.udacity.com/), see the [Completion Certificate](https://graduation.udacity.com/confirm/QCK3UKSS).

**Task:** build a pipeline to process real-world, user-supplied images. Given an image of a dog, the algorithm gives an estimate of the dog’s breed using a Convolutional Neural Network (CNN).

The solution is in the file [dog_app_my_solution.ipynb](https://github.com/viktor-begun/Deep_Learning_Dogs_Classifier_CNN/blob/main/dog_app_my_solution.ipynb).
The two other files [test_net.ipynb](https://github.com/viktor-begun/Deep_Learning_Dogs_Classifier_CNN/blob/main/test_net.ipynb) and [test_models.ipynb](https://github.com/viktor-begun/Deep_Learning_Dogs_Classifier_CNN/blob/main/test_models.ipynb) are the help files to check performance of different networks and of the final model pre-trained to a different level of accuracy.

Contents of the `dog_app_my_solution.ipynb` file:
- Import Datasets
- Detect Humans
- Detect Dogs
- Create a CNN to Classify Dog Breeds (from Scratch)
- Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Write the Algorithm
- Test the Algorithm

**Libraries and methods used:** `cv2`, `facenet_pytorch`, `glob`, `math`, `matplotlib.pyplot`, `NumPy`, `OrderedDict`, `os`, `PIL.Image`, `torch:` `.nn.functional`, `.optim`; `torchvision:` `.datasets`, `.models`, `.transforms`; `tqdm`.
 
