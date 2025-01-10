# my_ml_projects
machine learning and AI projects

 * 1. Heart Disease project : 
   contains a csv file with :
    x: 13 features (13,303)
    y: 303 binary targets (303,)
    pythone code : pythone1.ipynb
    model : RandomForestClassifier
    rsults : 'f1': 0.82, 'precision': 0.84, 'recall': 0.81\n
    model : LogisticRegrassion\n
    rsults : 'f1': 0.84, 'precision': 0.83, 'recall': 0.85
    executable model : Logistic_Regrassion_88.joblib
 *
 *
 * 2. bulldozer price prediction (time series) :
   contains csv files (Train, Test) with :
     x: 52 features (52,412698)
     y: 412698 regression targets (412698,)
     pythone code : bulldozerpython.ipynb
     model : RandomForestRegressor
     rsults : 'RMSLE : 0.24633298777862547
              ' mean_absolute_error : 5979.688239400049
              'mean_squared_error : 81482533.11468442
              'R2 : 0.8813716616684798
     executable model : model1_RMSLE_0.246.joblib
  *
  *
  * 3. dog breed identifier (CNNs) :
    contains csv files (labels, submissionformat), 10222 train photos, 13336 unlabled test photos with :
      x: 10222 photos
      y: 120 breeds 
      pythone code : dogbreedpyhton.ipynb
      model :Sequentioal "https://www.kaggle.com/models/google/mobilenet-v2/TensorFlow2/140-224-classification/2"
      rsults : kaggle's late submission score: rank 103 
      executable model : 2024-12-31 18:18:55-1000_images_mobilenetv2_Adam.h5
