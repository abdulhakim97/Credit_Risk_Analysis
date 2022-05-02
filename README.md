# Credit_Risk_Analysis
---------------------------------------------------------
# Overview of the analysis: 
### The plan of this project was to use differenet machine learning techniques to train and evaluate models. By using a cc credit dataset from LendingClub we can apply machine learning to solve a real-world challenge in figuring out the credit risk each one poses. In this challange we will be focused on supervised machine learning to analyze and predict credit risk. 

# Results: 
-----------------------------------
## for Random Oversampling
<img width="217" alt="Screen Shot 2022-05-01 at 11 32 40 PM" src="https://user-images.githubusercontent.com/96555487/166184674-04ec3b1b-c498-4cc0-bfe6-bc9a2a3091c3.png">
<img width="624" alt="Screen Shot 2022-05-01 at 11 32 59 PM" src="https://user-images.githubusercontent.com/96555487/166184680-982209d8-c2c4-4fd5-83dd-82ddc85debd5.png">
## for Smote Oversampling
<img width="213" alt="Screen Shot 2022-05-01 at 11 34 48 PM" src="https://user-images.githubusercontent.com/96555487/166184826-c3be838b-8cf3-49d7-b935-099470d92aae.png">
<img width="675" alt="Screen Shot 2022-05-01 at 11 34 57 PM" src="https://user-images.githubusercontent.com/96555487/166184828-97aa948b-bf63-4b92-9e8d-3860407e4c7c.png">
## for CC Undersampling
<img width="251" alt="Screen Shot 2022-05-01 at 11 36 32 PM" src="https://user-images.githubusercontent.com/96555487/166184916-fbc3102a-269a-47f2-a8e9-7a963f8c6ebb.png">
<img width="634" alt="Screen Shot 2022-05-01 at 11 36 41 PM" src="https://user-images.githubusercontent.com/96555487/166184921-743bd877-86eb-42bd-b5e0-e1f88118da6f.png">
## for Combination Smoteen
<img width="189" alt="Screen Shot 2022-05-01 at 11 37 51 PM" src="https://user-images.githubusercontent.com/96555487/166185018-018c0292-7cde-4471-bec1-0d9fed93294e.png">
<img width="629" alt="Screen Shot 2022-05-01 at 11 38 01 PM" src="https://user-images.githubusercontent.com/96555487/166185021-ec40693f-2e11-45c1-a674-c281c64b1cde.png">
## for BRFC
<img width="209" alt="Screen Shot 2022-05-01 at 11 39 48 PM" src="https://user-images.githubusercontent.com/96555487/166185156-79c6a927-bc06-4737-b612-c101da69932a.png">
<img width="668" alt="Screen Shot 2022-05-01 at 11 40 03 PM" src="https://user-images.githubusercontent.com/96555487/166185160-5baefb88-e0b7-4e26-ab62-f5f6fdf1fe04.png">
## for EEC
<img width="203" alt="Screen Shot 2022-05-01 at 11 40 49 PM" src="https://user-images.githubusercontent.com/96555487/166185215-0fff7316-0bf5-454a-996c-946218cc8ef9.png">
<img width="658" alt="Screen Shot 2022-05-01 at 11 40 55 PM" src="https://user-images.githubusercontent.com/96555487/166185219-4b8dbddb-4102-4494-8f41-7f3082ba9c3c.png">







# Summary: 
------------------------------------------------------
### From what I gathered collecting and sampling the data, the precision of low-risk indiviudal was pretty good, almost all of the low-risk cusomters were marked as low-risk however high-risk credit users weren't precicise at all.
The EasyEnsembleClassifier or the ECC had the highest Balanced Accuracy Score out of all the 6 models that were used. I would recommend that this model by used compared to the other five because of these reasones.
