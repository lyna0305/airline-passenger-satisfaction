#### This readme.txt file contains instructions on how the two best trained models models should be run on the test set. 

We have included all the files needed in the 'NECO Coursework' zip file to run the two best-trained models on the test set. 

### 'NECO Coursework' zip file contains:

- Best pre-trained SVM model (best_svm.pkl)
- Best pre-trained MLP model (best_mlp.pkl)
- Code to test the pre-trained SVM model (SVM model.ipynb) and corresponding HTML file (SVM model.html)
- Code to test the pre-trained MLP model (MLP model.ipynb) and corresponding HTML file (MLP model.html)
- Preprocessed test dataset (test_dataset.csv)
- Instructions on how the trained models should be run (readme.txt)
 

### Required software versions: 

pandas==2.1.1
numpy==1.26.0
matplotlib==3.8.0
matplotlib-inline==0.1.6
seaborn==0.13.0
scikit-image==0.22.0
scikit-learn==1.3.0
scipy==1.11.3
torch==2.0.1
torchvision==0.15.2a0
skorch==0.15.0
pickleshare==0.7.5
cloudpickle==2.2.1
async-timeout==4.0.2
jinja2-time==0.2.0


### Setup instructions:

- Extract all files from the 'NECO Coursework' zip file. 
- Open 'SVM model.ipynb' and 'MLP model.ipynb' files. These files contain code to test pre-trained SVM and MLP models. 
- Change directories (cd) to the extracted folder.  
- Install packages from requirements and import libraries by running code. 
- Import and preprocess the test dataset to prepare it for input into the respective models by running code. 

### Loading pre-trained model and testing on test set:

- Pre-trained SVM and MLP models are saved as 'best_svm.pkl' and 'best_mlp.pkl', respectively. 
- Load these models by running codes in 'SVM model.ipynb' and 'MLP model.ipynb' files.
- Test on test set by making predictions on test data. 
- Evaluate the models by looking at performance metrics and confusion matrices. 


