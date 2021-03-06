# Hostile-URL-Detector (HUD): a multi-staged URL analysis tool to provide useful insights about an input URL

* With the massive strides in digital technology and popularization of internet, data
  security and privacy comes under an alarming risk of being violated. Several attacks like
  phishing, defacement and malware have been a constant threat to the data of not only big
  corporations but also an internet using individual. These attacks are mostly motivated by
  financial gains like in the case of several phishing attacks where the link/URL (Uniform
  Resource Locator) may redirect the user’s data to a different hidden URL causing unwanted harm. 

* In this project we refer anything harmful whether financial, social or mental as **hostile**. 
  We have proposed a methodology to detect or classify an input URL into one of the attack types
  and provide the user with more information about the URL they are to visit. Here, we have made
  large set of labelled links (**1,89,780 URLs**- which is a combination of URLs taken from various
  sources and contains the types – **malware, malicious, adult, phishing, defacement and spam**)
  on which we perform lexical feature extraction to gain more information about the link (to
  extract literary features) and various novel features which we have proposed are also extracted.
  
* In total, we extracted 62 features and gained the highest predictive **accuracy of 99.54%** using random forest
  classifier. Other algorithms used were Gaussian Naive Bayes, Decision Tree Classifier, Multi Layer Perceptron Classifier and K-Nearest Neighbors.

## About the code

* Python was used to code the entire project as:
  * It gives easy access to supervised machine learning algorithms with **sklean** and libraries like **numpy** and **pandas**.
  * Provides **tkinter** to make simple GUI.
  * Easy to code and simple to understand data structures and computing logic. 
  
> ### NOTE:
  > * **Only the GUI** part has been uploaded which makes the application non functional, so, only the GUI will execute.
  > * Install sklearn, tkinter, themedtk and any other requirement console asks.
  > * Install **Audiowide** font.
  
## Screenshots 

### Architecture

![Architecture](https://user-images.githubusercontent.com/61655919/94439775-726b9800-01be-11eb-9109-60c9a1c91d42.png)

### Feature Extractor

![Feature Extractor](https://user-images.githubusercontent.com/61655919/94439937-ad6dcb80-01be-11eb-8a8d-331837e3ae2f.png)

### Home tab
![Screenshot (188)](https://user-images.githubusercontent.com/61655919/94446337-1e64b180-01c6-11eb-8aca-4b07fb4d4f76.png)

### Giving "google.com" as input and pressing Enter key

![Screenshot (183)](https://user-images.githubusercontent.com/61655919/94443970-6fbf7180-01c3-11eb-992a-d296318dd757.png)

### Giving adult URL as input (Stage-1)

![Screenshot (184)](https://user-images.githubusercontent.com/61655919/94442787-fd9a5d00-01c1-11eb-8aa8-bef40a54e0dc.png)

### Giving adult URL as input (Stage-2)

![Screenshot (185)](https://user-images.githubusercontent.com/61655919/94442918-26baed80-01c2-11eb-8c4b-3895243e8952.png)

### Performance display tab (Modelwise predictive accuracy for each URL type)

![Screenshot (186)](https://user-images.githubusercontent.com/61655919/94443204-844f3a00-01c2-11eb-8b2c-77a33c46ff84.png)

### Dependency checker tab

![Screenshot (187)](https://user-images.githubusercontent.com/61655919/94443660-0dff0780-01c3-11eb-9fdf-04e4221374af.png)

### History tab

![Screenshot (176)](https://user-images.githubusercontent.com/61655919/94471488-e6219b00-01e6-11eb-8809-95071315f600.png)







