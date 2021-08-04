# Machine-learning-soccer-regression
 Using regression to predict the pontuation and place of a soccer team in Campeonato Brasileiro de Futebol
 
> ## About The Project

I am a soccer lover so I decided to start a project using programming to try to predic with regression the final pontuation of the soccer teams that are participating in Campeonato Brasileiro de Futebol Série A, which is a running point championship with 38 rounds and 20 teams and a very hard one with 7 different winners in the past 18 years.
* This project was developed for the subject Introdução ao aprendizado de máquina e à mineração de dados (PO450) offered by the college Unicamp
> ## Built With

Python in Jupyter Notebook

I decided to try different machine learning approaches to compare the results, so i used linear regression, decision tree, random forest and XGBoost.
To get the data to train and to test my machine learning models I used web scraping from the site WorldFootball.net.

> ## Features and scores

![image](https://user-images.githubusercontent.com/88220952/128258316-353fe366-943b-4edb-b32a-66976dd4751f.png)

> ## Data for trai and test

X_train = atrib_norm[:4560] # 2013-2018

X_test = atrib_norm[4560:5320] # 2019

d_train = pontuacao[:4560] # 2013-2018

d_test = pontuacao[4560:5320] # 2019

* The year of 2020 was used as validation data

> ## Results

![image](https://user-images.githubusercontent.com/88220952/128260636-f23c23ff-7bf8-4aa1-baba-2b8f39f84ca7.png)

For the year of 2020 the models predicted the winner of the championship, Flamengo, from the data of the round 32:

![image](https://user-images.githubusercontent.com/88220952/128260543-d77dd283-d41f-4684-b823-5b45d080b48a.png)

The predictions for 2021 using data from round 12:

![image](https://user-images.githubusercontent.com/88220952/128260698-f449ee9b-6f98-46d0-b551-abb677a7509f.png)

