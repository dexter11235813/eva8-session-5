# eva8-session-5

This repo contains the refactored code from the Colab file in [assignment 4](!https://colab.research.google.com/drive/1oVt7T6tb90Y1EXvFaIWgm72emqZZPXi4?usp=sharing).

The code has been broken down into three separate files :- 



<h2 align = 'left'> model.py </h2>

The ```model.py``` file contains the pytorch model class. It is considered a good practice to keep all the model classes in the same file, and importing the relevant model in the main code. 

<h2 align = 'left'> utils.py </h2>

The ```utils.py``` generally contains various helper functions that are not model or analysis specific, and are expected to be reused across a project.

<h2 align = 'left'> S5.ipynb </h2>

The ```S5.ipynb``` file is the main file for this project, where the actual model training and evaluation happens. Given the constraints of the project structure, this file also contains the code for downloading data and preparing data loaders. 


<h2 align = 'center'> Model Metrics </h2>


### model summary 

![](/assets/model_summary.png)



### sample images from train dataloader 

![](/assets/sample_images.png)


### Training and Testing Curves

![](/assets/training_testing_curves.png)
