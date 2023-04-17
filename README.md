# DR-Swish-GFG

Project Description:

Diabetic retinopathy is a complication that affects the eyes due to high blood sugar called diabetic retinopathy. Visual acuity deteriorates, and in severe cases, blindness may occur. Early symptoms of diabetic retinopathy include blurred vision, cloudy vision, dark vision, and difficulty seeing colours. Manual detection of diabetic retinopathy by ophthalmologist takes plenty of time and patients need to suffer a lot currently. This project demonstrates research studies using a small open-source retinal imaging database for in-depth learning assessment. Goal is to build a machine learning model that can detect diabetic retinopathy condition. 
The project proposes an automated system to identify diabetic affected eye among the input retinal images.
The automated computer-aided detection of diabetic retinopathy uses a machine-learning hybrid model and is performed by extracting haemorrhagic, micro-aneurysm, and exudate features.
This project analyses the retinal images and look for the severeness of certain visible features that can help us identify the presence of the condition.
The project has a working CNN model using a Swish activation function for training the retinal images obtained from the open-source dataset.
Project is divided into four phases which is the Home Page, Predictor of DR, Q&A section for references and final is the statistics page.

Objectives: 

To raise awareness about diabetic retinopathy and its prevention: The project aims to spread awareness about the disease and detecting where a person has diabetic retinopathy based on its retinal images.

To provide essential information about diabetic retinopathy: The project aims to provide in-depth information about DR, its levels, causes, symptoms, complications, and treatment options to help users understand the disease better.

To predict diabetic retinopathy: The project includes a machine learning diabetic retinopathy prediction model that can predict whether a user has diabetic retinopathy or not based on the retinal images.

To reduce the burden of diabetic retinopathy: By providing these resources and tools, the project aims to help people to identify the risk of DR at an early stage and improve the quality of life for all people who have or are at risk for the disease.

Scope:

The website is designed to cater to the needs of people with diabetic retinopathy as well as those who want to prevent its onset. The website provides a variety of features, including a homepage which includes basic information about DR, a machine learning diabetic retinopathy prediction model, a Q&A section for reference of the user and statistical information about DR. The website's scope is limited to providing information and tools related to diabetic retinopathy prediction, and it does not intend to replace professional medical advice. The website is accessible to everyone, and retinal images of users of all age group having diabetes can be uploaded for prediction. The website's focus is on providing accurate and reliable information and tools to help people to identify their condition and prevent its onset.

Methodology:

Python Streamlit was used for web development

●	These technologies were used to create an interactive and user-friendly website
●	The design is intuitive and easy to navigate
●	The website features include Homepage, DR predictor, Q&A section, and Statistical Info

Machine learning diabetic retinopathy prediction model

●	Data Collection: The first step in building the diabetic retinopathy prediction model is to collect the relevant data. The dataset named Diabetic Retinopathy Gaussian Filtered used for training the machine learning model was picked from the Kaggle. The data includes retinal images of various levels such as mild DR, Proliferate DR, Severe DR, Moderate DR, and No DR.

●	Data Pre-processing: It involved the process of cleaning and removing any missing values, duplicates, or irrelevant features. The project also scales and normalises the data to ensure that each feature has equal importance in the prediction model.

●	Data Splitting: The project splits the pre-processed data into three sets: training set, validation set and testing set and their ratio is 60%,15%,25% respectively. The training set is used to train the CNN model, while the testing set is used to evaluate the performance of the model.

●	Model Training: Model uses Swish activation function for training and Sigmoid for prediction. Model composes of multiple layers such as input layer, max pulling layer, convolutional layer, flatten layer, dense layer, and prediction layer.

●	Model Evaluation: The project evaluates the performance of the CNN model on the testing set. The project uses various performance metrics precision, recall, accuracy, and loss function.

●	Deployment: Finally, the project deploys the CNN Model on the website made using Python Streamlit, where users can input their retinal images, and the model predicts their diabetic condition.

Results:

After training the CNN model on the Diabetic retinopathy gaussian filtered dataset, we obtained an accuracy of 95% on the test set. This means that the model is able to correctly predict the diabetic retinopathy status of a patient in 95% of cases, based on their retinal images. The Swish activation function has increased the accuracy of the training model as compared to the Relu activation function.

This information can be useful for healthcare professionals in identifying risk factors for diabetic retinopathy and recommending preventive measures to patients. For example, if a patient has high DR level, they may be advised to take professional advice, or even start medication and prevent the onset of diabetic retinopathy.

Overall, the CNN model on the Diabetic retinopathy gaussian filtered dataset has shown promising results in predicting the diabetic retinopathy status of patients based on their retinal images. With further improvements and optimizations, this model could potentially be used as a tool for early detection and prevention of diabetic retinopathy in clinical practice.
