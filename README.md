# mnist_with_tensorflow-Jupyter
this is a jupyter notebook for mnist classification using tensorflow

**original file : https://github.com/Jin0316/Algorithm**



## Description 

there are 3 models in this jupyter notebook using tensorflow(keras). 

we try **model 3**, and plot classification results.

## models summary

  * model 1
  
![Model 1](/model_summary/model_1.PNG)

  * model 2
  
![Model 2](/model_summary/model_2.PNG)

  * model 3
  
![Model 3](/model_summary/model_3.PNG) 

## 1. Create Model 3 
we create model with 7 layers and 4 convolutional layer

![Create Model 3](/model_3_specifications/model_code.PNG) 

## 2. Train Model  
we train for 5 epochs

![Training Model 3](/model_3_specifications/training.PNG) 

## 3. Test Model  
testing with 10000 testing data 

![Testing Model 3](/model_3_specifications/testing.PNG) 


## classification results
  
### plot correct results

![Model 3 Correct](/model_3_specifications/correct_plot.PNG)
  
### examples
     
* error examples
      
    ![Error Examples](/model_summary/m3_wrong.PNG)
    
* correct examples
      
    ![Correct Examples](/model_summary/m3_correct.PNG)

# 3 Line Summary

1. create model with 7 layers including 4 convolutional layers
2. test 5 epochs, final test loss: 0.0325, final test accuracy: 0.9902
3. testing accuracy : 0.9889
