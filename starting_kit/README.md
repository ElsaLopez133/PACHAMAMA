# Starting kit for Insects Classification Challenge


This challenge uses a Dataset introduced by  Maria-Elena Nilsback and Andrew Zissermanfor un the paper **Automated  flower  classification  over  a  largenumber  of  classes**,  
 
 
The dataset coniststs of total of 8,189 images belonging to 102 classes that  are  commonly  occuring  in  the  United  Kingdom. Some of the classes are the following:

1. Buttercup
2. Fire lily
3. Azalea
4. Gaura
5. Garzania

    
This challenge is about creating and predicting a Machine Learning model and train it with the data provided to be able to identify and classify living species.


### Phases
This challenge conists of two phases:  

1. `Development Phase`
In this phase you can train a model and submit at most 20 submissions per day to check the score of your model and to see how good your model is performing. Once you are satisfied with your performance then you can try the Final Phase.
    
2. `Final Phase`
In this phase you can submit only once so it is advised to do it when you are ready for the final submission.
    
    

### References and credits: 

 
1. Automated  flower  classificationover  a  large  number  of  classes (https://www.robots.ox.ac.uk/~vgg/publications/2008/Nilsback08/nilsback08.pdf)       
2. Université Paris Saclay (https://www.universite-paris-saclay.fr/)
3. ChaLearn (http://www.chalearn.org/)


### Prerequisites:
Install Anaconda Python 3.6.6 


### Usage:

(1) If you are a challenge participant:

- The file README.ipynb contains step-by-step instructions on how to create a sample submission for the Bees and Wasps Image Classification challenge. 
At the prompt type:
jupyter-notebook README.ipynb

- modify sample_code_submission to provide a better model or you can also write your own model in the jupyter notebook.

- zip the contents of sample_code_submission (without the directory, but with metadata), or

- download the public_data and run (double check you are running the correct version of python):

  `python ingestion_program/ingestion.py public_data sample_result_submission ingestion_program sample_code_submission`

then zip the contents of sample_result_submission (without the directory).

(2) If you are a challenge organizer and use this starting kit as a template, ensure that:

- you modify README.ipynb to provide a good introduction to the problem and good data visualization

- sample_data is a small data subset carved out the challenge TRAINING data, for practice purposes only (do not compromise real validation or test data)
