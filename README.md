# cs128h-final-project
<h3> Group name: TBD <h3>
<h3> Group member: Roy Xiong(sx24) <h3>
<h3> Project Introduction: <br>
I'm a big basketball fan, and I think it would be pretty cool if I could use machine learning to predict the outcome of NBA games(so that I can show-off to my friends). Since I'm new to the machine learning, I plan to mainly focus on implementing neural networks for the prediction. And if time allows, I would try to use other models to cross-examine the best method with highest accuracy. The main goal is really finishing the project and then try to tune the model for better performance. Hopefully I would have a solid grasp of machine learning by the end.  
<h3>
<h3> Technical Overview: <br>
- build data-crapping tool to collect data, or retrieve data from official datasets: collection -> visualization -> preprocessing --> scaling<br>
- write a database to store the data: splitting the datat into training, test, and validation sets (*checkpoint 1*)<br>
- use pandas for data analysis <br>
- implementing the model with the tensorflow/rust, nalgebra (exisiting crates) <br>
- model training (*checkpoint 2, hopefully*)<br>
- corss-validation and tuning(not sure about the details yet) <br>
- predict the most recent game!

<h3>
<h3> Possible Challenges:<br> 
- Most of the machine learning projects(especially related to this topic) are done in python, so by far I haven't discover many references or detailed examples on how to implement a specific model/algorithm in rust. <br>
- The rust neural network crates are largely experimental, so it is possible that I have to write certain functionalities on my own. <br>
- Probably need to do a lot of reading and digging on theories :(
<h3>
<h3>References: <br>
https://github.com/kyleskom/NBA-Machine-Learning-Sports-Betting.git <br>
https://medium.com/nerd-for-tech/predicting-the-outcome-of-nba-games-using-machine-learning-676a62549040
<h3>
