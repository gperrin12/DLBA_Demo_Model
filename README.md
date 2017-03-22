# DLBA_Demo_Model
Detroit Land Bank Authority (DLBA) Demolition Model Code
This is a repository of the ipython notebooks I've used to create the DLBA demolition model for February 2017. One notebook (demo_model_032217.ipynb) uses Motor City Mapping data (https://www.motorcitymapping.org/#t=overview&s=detroit&f=all) as inputs into the model. The other notebook (demo_model_no_MCM_032217.ipynb) does NOT use Motor City Mapping data, as a test to see how the model changes, as (I believe) Motor City Mapping is gradually losing funding and will slowly be phased out in the future. 

The model with Motor City Mapping data has the following precision and accuracy on a slice of test data:

Precision = 95.67%

Accuracy = 95.06%

The model with NO Motor City Mapping data has the following precision and accuracy on a slice of test data:

Precision = 92.68%

Accuracy = 93.61%

So, there is some loss in accuracy and precision by losing out on the Motor City Mapping data (namely, the building conidition attributes), but it is not significant. 

Below is a map showing the output of the demo_model_032217.ipynb notebook showcasing where likely blighted houses exist.
![blight map](https://cloud.githubusercontent.com/assets/9039296/23921697/fa6039cc-08d5-11e7-8e46-2046415dbfb9.png)
