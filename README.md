# Binary-Classification-of-Patients-in-Diabetes-Dataset

## Table of Content
<ul>
  <li>
    <a href="#Overview">
      <span>1. Overview</span>
    </a>
  </li>
  <li>
    <a href="#Dataset">
      <span>2. Dataset</span>
    </a>
  </li>
  <li>
    <a href="#Motivation">
      <span>3. Motivation</span>
    </a>
  </li>
  <li>
    <a href="#Aspects">
      <span>4. Technical Aspects</span>
    </a>
  </li>
  <li>
    <a href="#Credits">
      <span>5. Credits</span>
    </a>
  </li>
   
</ul>

<h3>
  <span id="Overview">Overview</span>
</h3>

> To predict if a patient has diabetes or not, a model based on *Rnadom Forest Classifier* , `./diabetes_model.pkl` has been built. In this project, a comparative analysis has been done on various algorithms like `Logistic Regression`, `Random Forest Classifier`. The best model is buil on the RFC algorithm. It's AUC value is 98.17%.

<h3>
  <span id="Dataset">Dataset</span>
</h3>

> The diabetes dataset used in this exercise is based on data originally collected by the National Institute of Diabetes and Digestive and Kidney Diseases. This data consists of diagnostic information about some patients who have been tested for diabetes. Scroll to the right if necessary, and note that the final column in the dataset (Diabetic) contains the value 0 for patients who tested negative for diabetes, and 1 for patients who tested positive. This is the label that we will train our model to predict; most of the other columns (Pregnancies,PlasmaGlucose,DiastolicBloodPressure, and so on) are the features we will use to predict the Diabetic label.

<h3>
  <span id="Motivation">Motivation</span>
</h3>

> Diabetes is a chronic disease with the potential to cause a worldwide health care crisis. According to International Diabetes Federation 382 million people are living with diabetes across the whole world. By 2035, this will be doubled as 592 million. Diabetes mellitus or simply diabetes is a disease caused due to the increase level of blood glucose. Various traditional methods, based on physical and chemical tests, are available for diagnosing diabetes. However, early prediction of diabetes is quite challenging task for medical practitioners due to complex interdependence on various factors as diabetes affects human organs such as kidney, eye, heart, nerves, foot etc. Data science methods have the potential to benefit other scientific fields by shedding new light on common questions. One such task is to help make predictions on medical data. Machine learning is an emerging scientific field in data science dealing with the ways in which machines learn from experience. The aim of this project is to develop a system which can perform early prediction of diabetes for a patient with a higher accuracy by combining the results of different machine learning techniques

<h3>
  <span id="Aspects">Technical Aspects</span>
</h3>

> This exercise/project has two main sections. In the first part, box-plot on various features have been drawn. From this, we can notice a high density of outliers is present in the non-diabetic class.  In particular, Pregnancies and Age show markedly different distributions for diabetic patients than for non-diabetic patients. These features may help predict whether or not a patient is diabetic.<br>In the next portion, logistic regression and random forest classifier has been implemented! At last, a pipeline has been implemented.

<h3>
  <span id="Credits">Credits</span>
</h3>

> The diabetes dataset used in this exercise is based on data originally collected by the National Institute of Diabetes and Digestive and Kidney Diseases.
