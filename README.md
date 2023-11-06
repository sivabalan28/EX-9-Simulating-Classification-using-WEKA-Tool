# EX-9-Simulating-Classification-using-WEKA-Tool
# Date:
# AIM:
To perform a classification technique using WEKA tool

# WEKA:
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements. WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram − image

# CLASSIFICATION:
Classification in data mining is a common technique that separates data points into different classes. It allows you to organize data sets of all sorts, including complex and large datasets as well as small and simple ones. It primarily involves using algorithms that you can easily modify to improve the data quality. This is a big reason why supervised learning is particularly common with classification in techniques in data mining. The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a number of classes or groups. Such as, Yes or No, 0 or 1, Spam or Not Spam, cat or dog, etc. Classes can be called as targets/labels or categories.

# PROCEDURE:
1.Load the data file into the WEKA explorer. The data can be loaded from the following sources − Local file system Web Database

2.Click on the "Open file" button. A directory navigator window opens as shown in the following screen 
![280527955-6170b03b-e43d-4375-a959-819abd1edab0](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/791e2849-7b52-4958-8e22-baf7e408ef30)

3.Click on the Classify tab, and you would see the following screen 
![280527975-8fff2e27-f03d-49a7-beea-d70418978881](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/7738d2cd-6c54-417e-96f6-727eaf12d61c)

4.Now, keep the default play option for the output class  
![280527996-2fa1e8c0-0311-4b10-8317-0a2fcfcfd771](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/f13f80e4-1746-4729-b48e-72aec0202893)

5.Click on the Choose button and select the following classifier − weka→classifiers>trees>J48. 
![280528019-24ee8f14-1f4b-4e16-b49a-cc46a76d7324](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/c7d634ba-80e9-419a-a7c1-0df131609575)

6.Click on the Start button to start the classification process. After a while, the classification results would be presented on your screen as shown here  
![280528073-5506b885-a093-4157-a2e6-ed24fc625017](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/efeeb2c3-0ba2-4555-bb8f-e17f5dbb38cc)

7.To see the visual representation of the results, right click on the result in the Result list box. Several options would pop up on the screen as shown here  
![280528098-07f8b1e5-38f5-4b71-ac10-9c7e6ced5ab1](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/b318bebc-f403-46fc-99d9-6407416b6f05)

8.Select Visualize tree to get a visual representation of the traversal tree as seen in the screenshot below  
![280528116-5cb6b605-0a67-4dfe-9a40-5fa7445ae061](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/1802ac1a-2a04-4568-a07c-00532b2d34d7)

9.Selecting Visualize classifier errors would plot the results of classification as shown here 
![280528137-b4b02ea2-f2e6-49e1-9ea0-e475edf86acc](https://github.com/sivabalan28/EX-9-Simulating-Classification-using-WEKA-Tool/assets/113497347/f8b23962-c132-48c3-b3d3-1d9af2fbe205)

10.A cross represents a correctly classified instance while squares represents incorrectly classified instances. At the lower left corner of the plot you see a cross that indicates if outlook is sunny then play the game. So this is a correctly classified instance.

# RESULT:
Thus the simulation of classification technique has been executed using WEKA tool successfully
