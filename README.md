# LinearRegresison
Study Using Linear Regression model with sklearn to predict something with me.
Here are the some code of Linear Regression that I've coded also studied it.
Although the purpose of this is predict value, I also want to visualizate it into two types that is line and parabole, with formula and with
library on sklearn (I've studied it on DLLT courses)

#Pros and cons of this algorithm:

Pros:

- Very easy to understand with visualizate by line and parabole
- Effectively on almost dataset

#Cons:

- If you've read via my code (draw line and parabol), I used the formula and it need to calculate inverse on it, if data is so complicated --> calculate inverse of matrix take so much resource of computer (maybe can solve this problem by using gradient descent, i'll code it later).
- If the dataset isn't good, so the line will be very worse, right? Only one data is under so much with another point, the line will decrease so farrr.
- Mention that, if you want to draw cubic graph, it's possible, but, that'll lead to overfiting problem, that mean you do is only for draw line via all of that point, not good for predict value of another point (data point).


#Something about plot
Using np.linspace to create so much point on that.

#With Linear Regression with formula:
- Prototype formula of this model: x = (((A^T).A)^-1).(A^T).b
- With A,b corresponding with line is [[x1 1]] and b is [[1]], parabole [[x1^2 x1 1]]
- This formula also right with cube graph.

#With Linear Regression sklearn
- Only need change data into suitable with form on sklearn.
- It only take X and y [[x1,x2]] [[y1]] and will increase corresponding with parabole or cube....
- It's all of linear regression I know.


#This formula is in subject Mathematics for AI
