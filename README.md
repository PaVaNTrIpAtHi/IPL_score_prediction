Score prediction of IPL team with flask app
IPL has been a huge success in India and the best cricket league in the world. Why not build something which can help us use our skills of machine learning. So, we created a score prediction web app which can predict score of an IPL team by getting some details like runs scored in 5 overs, wickets down and give us a range of the score that the score of the team would be in this range. We used flask for web development and generated the main page.

Dataset Description: 
The dataset contains ball by ball data of IPL matches from 2008 – 2017. It has 15 rows like date of match, runs scored in that ball, result of the match. Total is our target column which we have to predict.
![image](https://user-images.githubusercontent.com/88571564/180371047-c221e970-0ae9-4f9f-9726-dd0f6c739a3b.png)
 

Algorithm Description:
Linear Regression:
Linear regression is a supervised learning machine learning algorithm. It performs the task to predict dependent variable (y) with respect to other independent variables (x …. Xn). It helps us find out a relationship between the dependent and independent variables. 
The equation is Y = C+w1X + ….WnXn
![image](https://user-images.githubusercontent.com/88571564/180371061-d14d06d9-4912-4169-937f-65dcbcdf1cd5.png)
 
Linear regression tries to find the best fit line where you get minimum error. To read more about Linear regression, check this link https://www.geeksforgeeks.org/ml-linear-regression/
How to Execute?
So, before execution we have some pre-requisites that we need to download or install i.e., anaconda environment, python and a code editor. Anaconda: Anaconda is like a package of libraries and offers a great deal of information which allows a data engineer to create multiple environments and install required libraries easy and neat.
To check on how to install anaconda environment, set up jupyter notebook refer to this article. You can skip the article if you have knowledge of installing anaconda, setting up environment and installing requirements.txt
1.	Install necessary libraries from requirements.txt file provided.
 
2.	Go to the directory where your requirement.txt file is present.
<<directory of your file>>:  E.g, If my file is in d drive, then 
1.  d:
2. cd d:\License-Plate-Recognition-main    #CHANGE PATH AS PER YOUR PROJECT, THIS IS JUST AN EXAMPLE
If your project is in c drive, you can ignore step 1 and go with step 2.
Eg. cd C:\Users\Hi\License-Plate-Recognition-main #CHANGE PATH AS PER YOUR PROJECT, THIS IS JUST AN EXAMPLE
 
3.	Run command pip install -r requirements.txt or conda install requirements.txt (Requirements.txt is a text file consisting of all the necessary libraries required for executing this python file. If it gives any error while installing libraries, you might need to install them individually.)
 
All the necessary files will get downloaded. To run the code, open anaconda prompt. Go to virtual environment if created or operate from the base itself.
Type cd path-to-project-file and then “python app.py”. All the steps are shown in the image below.
 
When you run the main.py file, you get a link.
Copy and paste the link to get the results.
http://127.0.0.1:5000/ Note: Link can be different on your computer.
Results:
1.	Display page
![image](https://user-images.githubusercontent.com/88571564/180371089-33a52b03-4e4e-459d-b5ee-4133af89a8a7.png)
 
2.	Enter values
![image](https://user-images.githubusercontent.com/88571564/180371100-a7ec7990-dae1-4220-84f3-d3b63a9cdf85.png)
 
3.	Predictions
 ![image](https://user-images.githubusercontent.com/88571564/180371127-7796952a-b03b-4b40-9a73-0972ad1738e1.png)

Issues faced/ Points to note:
1.	Go to the current working directory (path of your project) to run main.py
2.	Ensure you have all libraries installed.

Credit to https://www.analyticsvidhya.com/blog/2021/10/building-an-ipl-score-predictor-end-to-end-ml-project/ for the article 
and https://github.com/DevloperHS/ipl-demo github repository for the code. You can view this page for more details.

