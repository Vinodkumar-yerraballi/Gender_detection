# Gender_detection
Dataset link : https://www.kaggle.com/datasets/cashutosh/gender-classification-dataset

### **Gender   Detection Using Convolutional Neural Network
In this notebook let's predict the image is predict male or women. To do this I've used CNN**

****Our age prediction CNN model shall be defined and trained by**:
1. Importing **training and test datasets** from Google Drive Input Sub-folder
2. **Training dataset is already augmented** and has 234,000 images
3. **Greyscaling images** instead of using RGB color images
4. Defining our intuitively **distributed classes of age-ranges**
5. Using **60 epochs** on our **optimized CNN Architecture**, comprising of:
    - an input *Conv2D* layer (with 60 filters) paired with an *AveragePooling2D* layer,
    - a *MaxPooling 2D* layer,
    - 1 *Dense* layer with 132 nodes, and
    - an output *Dense* layer with 7 nodes.**
    
    
    ***Conculsion***
The dataset is takenfrom the kagele soure, this is a calssification problem to predict the image is men or women. Firstly we resacale the image with imagedatagenerator after that we load the data with some parameter such as target_size,batch_size etc.Then we install the sequential model in the model we conv2d,maxpooling2d,faltten layer,and finally add dense layer after that we complile the model and then fit the model with 10 epochs, we get arround **91% accuracy score to the model**, then create a function to predict the image is men or non women, our model is predict the good result of the inputimages.
