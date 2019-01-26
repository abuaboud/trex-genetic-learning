# T-Rex Genetic Deep Learning
AI teaches  itself to play a simplifed version of the popular chrome game (T-Rex) by  playing randomly and trying to pass down the good characteristics to the new generation of T-Rexs
 
#### Preview
 [![IMAGE ALT TEXT](http://img.youtube.com/vi/rGyPA6ocQKY/0.jpg)](https://www.youtube.com/watch?v=rGyPA6ocQKY)
 
#### Breif Techinical overview:
There might be other ways to make an AI for this game but I used Genetics as a cool experiment, it starts by initlizating many random neural network, I found out that there is a linear correclation between variables ,so my nueral network architecture is 2 inputs and 1 output (Sigmoid Activiation Function) which represents jumping or not
jumping
Algorithms Steps
- Let new generation play the game
- Evaluate each gnommes by giving fitness score
- Crossover between top gnomes
- Mutate them
- Repeat!
 
#### CrossOver
I tried  a couple of crossovers , the one I am using is either keep using same main gentics , or take average of both parents.
#### Mutate
I multiply the weights in the neural network by a random change rate .
#### Fitness Score
I am using the ratio between the number of obstacles it jumped over and the number of times space was pressed multiplied by game score , the reason I used the ratio is to eliminate jumpers gnomes.
 
#### Source files
- brain.py contains learning algorithm
- main.py contains game
- constant.py contains contsant variables
 
#### Todos
 - Do more analyzing to make sure it converges to the optimal solution.
 - Add birds into the game.
 
#### References
- https://github.com/shivamshekhar/Chrome-T-Rex-Rush