# Simple 2-input single layer Perceptron

In my introduction to artificial intelligence class during my computer science studies I was tasked with calculating output of 2-input single layer perceptron by hand. As with all hand calculations they were prone to errors. What's more - I had no way to check, whether my calculations were correct. I searched for similar program on the web with no results. Therefore, I decided to create one for myself. Probably I could have found a library for this task, but I thought that it will be a good learning project nevertheless. You may find this notebook useful if you are tasked with similar problem.

This notebook solves the problem of presenting the user with results and visualisation of all the steps that perceptron algorithm took while calculating the decision boundary for 2 input points.

 It is a simple example, and I do not guarantee its correctness. It works but further testing is required. I am by no mean an expert in the field of machine learning, deep learning or artificial intelligence. I created this notebook as a way to reinforce my learning and provide myself with visual representation and steps that perceptron took to get to the solution. Descriptions provided may not be accurate, may lack sufficient details and in some cases may be plainly wrong.  As I mentioned earlier this notebook might be useful to someone who is a student, tasked with calculating perceptron outcome by hand, to check whether their calculations are correct or not.

## Usage

The whole project is contained in a single jupyter notebook.
It can be cloned, or ran directly from Binder.

### Launching the notebook on Binder

To launch the interactive notebook, simply click the badge below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kielx/2-Input-Single-Layer-Perceptron/HEAD?labpath=Perceptron.ipynb)

It might take a while (20-30 seconds) to launch the notebook.
After its done you should be presented with view similar to the one below:
![Launched notebook](https://raw.githubusercontent.com/Kielx/2-Input-Single-Layer-Perceptron/da6a31a0ae57329f2f873c8e248db1dbfae8dcab/screenshots/Instruction1.png)

Next you should update the code in the notebook, specifying the input values:

![Adjusting input values](https://github.com/Kielx/2-Input-Single-Layer-Perceptron/blob/da6a31a0ae57329f2f873c8e248db1dbfae8dcab/screenshots/Instruction2.png?raw=true)

Then you need to run the notebook again by selecting Run All Cells option:

![Running the notebook](https://github.com/Kielx/2-Input-Single-Layer-Perceptron/blob/master/screenshots/Instruction3.png?raw=true)

Finally, you should be presented with updated values and new set of plots:

![Final result](https://github.com/Kielx/2-Input-Single-Layer-Perceptron/blob/master/screenshots/Instruction4.png?raw=true)

You can play around with the input values and see how the perceptron algorithm changes the output. After each adjustment you should run the notebook cells again and see the changes.