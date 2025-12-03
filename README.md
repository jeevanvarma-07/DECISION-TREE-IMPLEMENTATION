# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: JEEVAN VARMA

*INTERN ID*: CT04DR2749

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

##The goal of this internship task was to create, train, visualize, and assess a Decision Tree Classification Model utilizing a preferred dataset. The Heart Disease Dataset—which comprises 1025 lines of patient data and 14 medical characteristics including age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, ECG results, and more—was used for this project. The model seeks to forecast whether a patient is expected to develop heart disease (target = 1) or not (target = 0). This activity serves also as a foundation for grasping more sophisticated ML methods, since it shows how machine learning can be used to actual medical issues. 
 
 Python served as the programming language and Jupyter Notebook as the development environment for my successful execution of the project. Because it lets you write code, run it step by step, and view results all in one location, Jupyter Notebook is a strong data science tool. Pandas for data manipulation, NumPy for numerical calculations, Matplotlib and Seaborn for charting and visualizing, and Scikit-learn for applying the machine learning algorithm all helped me for this project. Among the most well-known and newbie-friendly ML libraries, scikit-learn offers a simple means of construction and assessment of Decision Trees and other such models. 
 
 Loading the CSV data into a pandas DataFrame signaled the start of the process. An early Exploratory Data Analysis (EDA) was carried out following loading to get to know the form of the data, the significance of every element, the target distribution, and to look for missing values. Deeper knowledge of the data was obtained by means of visuals like bar graphs, histograms, and a correlation heat map. Before training any machine learning model, one very crucial first step is to grasp the data. 
 
 Then the dataset was split into features (X) and target labels (y). Here, all the medical characteristics save the "target" column were fed into the model; the "target" column functioned as the output variable the model aims to estimate. Employing Scikit-train's train_test_split technique, the dataset was then divided into training and testing sets in an 80:20 ratio. The model is taught using the training data, and the testing data is used to gauge how well the model performs on unseen data.

 Then one built a Decision Tree Classifier with a maximum depth of 4. By dividing the data according on the feature having the lowest impurity or the highest information gain, the Decision Tree algorithm operates. Until a stopping condition is met, it continuously divides the data into branches. The tree illustrates visually the step-by-step decision-making process. 
 
 Predictions on the test set were made following training of the model, then evaluated using the accuracy score, classification report, and confusion matrix. While the categorization report displays precision, recall, and f1-score for every class, accuracy indicates how many predictions were right. The confusion matrix graphically represents how many samples were wrongly or correctly categorized. For this kind of dataset, the model's about 85% accuracy is seen as excellent. 
 
 Scikit-plot_tree's function then depicted the decision tree, noting the splits, gini impurity, sample count, and predicted class at each node. One of the main benefits of decision trees is that this helps the model be understood and easy to interpret. 
 
 Many fields—including marketing segmentation, risk forecasting, loan approval systems, fraud detection, and medical diagnosis—can use this assignment. Decision Simple, understandable, and suited for classification issues, trees abound.
