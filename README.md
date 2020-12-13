# mobile_price_classification_gcp

This is a classification use case which will classify price range of Mobile based on various features.
There are 3 clacces. i) Below 10k  ii) Between 10k-20k  iii)Above 30k

### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

### Project Structure :

#### Model_Final

This Folder Is Deployable File On Google GCP Cloud.

1.templates

i) indext.html -- HTML for taking input from user

ii) predict.html -- HTML form for showing predictions

2. main.py - This contains Flask APIs that receives student details through GUI or API calls, computes the precited value based on our model and returns it.

3. model_final.ipynb - This contains code of model training and model testing.

4. model.pkl - contains our serialized trained model which will be used for making predictions.

5. requirements.txt - contains name of libraries which will get installed while deployment of application.

6. app.yaml - A mandatory file required when app is getting deployed on 'Google GCP Cloud'.

#### Data_Preprocessing

Data_Preprocessing.ipynb - Contains jupyter notebooks of EDA and all dataset Preprocessing and also scaled data.

#### Finding_Best_Model

Model_Selection.ipynb - A jupyter notebook Where i have applied many Classification algorithms to find out which algorithm gives best accuracy.

#### Dataset

Contains Dataset.

### Running a File

Goto -- Anaconda Propt

Type -- cd "Path where file is saved"  then click enter

Then you will be on that path

Then type command
~~~
python app.py
~~~

App will start running and it will generate following local url

~~~
http://localhost:5000/
~~~

Enter this url on any browser, then you will see user input form.


#### This File is a deployable file on Heroku cloud

#### Click below link and make some predictions :)

[Click Here](https://mobile-price-prediction.el.r.appspot.com/)


