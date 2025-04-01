# Advanced Statistical Inference 


This course focuses on the principles of learning from data and quantification of uncertainty, by complementing and enriching the Introduction to Statistical Learning course. 
The presentation of the material follows a common thread based on the probabilistic data modeling approach, so that many classical algorithms, such as least squares and k-means, can be seen as special cases of inference problems for more general probabilistic models. Taking a probabilistic view also allows the course to derive inference algorithms for a class of nonparametric models that have close connections with neural networks and support vector machines. 
This advanced course is complemented by these lab sessions to guide students through the design and validation of the methods developed during the lectures.


### [Suggested] Google Colab
[Google Colab](https://colab.research.google.com/) is the suggested way to edit and execute the labs. Simply click on the icon to open the corresponding notebook in Colab. 

| Week | Subject  | Link |
|:-----|:---------|:-----|
| **Week 0** | Introduction to Python/Numpy  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eurecom-ds/asi-labs/blob/master/lab_week0/Tutorial_Python.ipynb)|
| **Week 1** | Bayesian linear regression    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eurecom-ds/asi-labs/blob/master/lab_week1/Bayesian_Linear_Regression.ipynb)|
| **Week 2** | Logistic regression with MCMC | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eurecom-ds/asi-labs/blob/master/lab_week2/Bayesian_Logistic_Regression_MCMC.ipynb)|


> [!TIP]
> Remember to save a copy of the notebooks when you are done, so that you can access them later ("File" -> "Save a copy in Drive" or "File" -> "Download .ipynb").

### [Optional] Fork the repository

If you want to save your changes on Github, you can fork the repository by clicking on the "Fork" button at the top of the page. 
This will create a copy of the repository in your GitHub account, where you can make changes and save them.

> [!IMPORTANT]
> If you fork the repository, open the notebooks from Google Colab "File" menu, selecting "Open notebook" -> "GitHub" and choosing your forked repository. This way, the changes you make will be directly saved in your forked repository.

### [Advanced] Local installation

The labs are designed to be executed in Google Colab, so you don't need to install anything on your local machine.
If you prefer to work on your local machine, you can clone the repository and install the required dependencies manually. 
A Dockerfile is provided to create a container with all the required dependencies.
A `devcontainer` configuration is also provided to use Visual Studio Code with the Docker container. 
For more information, check the [devcontainer documentation](https://code.visualstudio.com/docs/remote/containers).

> [!CAUTION]
> **Note**: The labs are designed to be executed in Google Colab. If you encounter any issues while running the labs locally, we won't be able to provide support.



