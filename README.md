## **Coursera Online Course --- Machine Learning by Andrew Ng**

This repository contains the lecture slides of Machine Learning course by Andrew Ng on Coursera(https://www.coursera.org/learn/machine-learning?), and some programming work based on it. The course assignment is originally performed in Octave software. I reproduced the same tasks in Python in order to 1) get more familiar with Python syntax; 2) get a better intuition of the knowledge learnt.

Topics covered by the slides include: Regression (Linear Regression with One Variable, Linear Regression with Multiple Variables), Classification (Logistic Regression, Neaural Networks, Support Vector Machines), Clustering, Dimensionality Reduction, Regularization, Bias/Variance Tradeoff.     

Basic algorithms covered by the course include: Batch Gradient Descent, Normal Equation, Forward Propagation, Back Propagation, Simplified Sequential Minimal Optimization (SMO) Algorithm, K-means, Principal Component Analysis.            

More advanced optimization methods, such as Conjugate Gradient, BFGS, L-BFGS, etc., are not illustrated, since they are way more complicated. We're encouraged to use libraries, rather than write them ourselves unless you're an expert in numerical computing.

Decision Tree, another classification method, is not covered by this course. So I picked it up in another Machine Learning course on Coursera.



**Below is the table of contents:**

- ### **Linear Regression with One Variable**

    [Lecture Slides](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%202.pdf)
    
    [Implementation in Python](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Linear%20Regression%20with%20One%20Variable_2.ipynb)
    
    -- **Tasks performed:** Read in CSV source file, visualize the relationship between X and Y in scatter plot, cost function implementation, Gradient Descent.
    
    -- **Data manipulations skills covered:** Data type conversion, scatter plot, contour plot, iteration. 
    

- ### **Linear Regression with Multiple Variables**
    
    [Lecture Slides](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%204.pdf)

    [Implementation in Python](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Linear%20Regression%20with%20Multiple%20Variables_2.ipynb)
    
    -- **Tasks performed:** Read in CSV source file, horizontally stack two data sets, feature normalization, cost function, Gradient Descent, visualize the cost function variations over iterations.
    
    -- **Data manipulation skills covered:** Data type conversion, data append, vector computation, plot.
    

- ### **Logistic Regression**
    
    [Lecture Slides](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%206.pdf)
    
    [Implementation in Python](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Logistic%20Regression_2.ipynb)
    
    -- **Tasks performed:** Read in CSV source file, visualize the two classes in scatter plot, cost function without regularization, cost function with regularization, Gradient Descent without regularization, Gradient Descent with regularization, BFGS implementation using the library, plot the linear decision boundary, make predictions with the optimal parameters, feature mapping, plot the non-linear decision boundary, visualize overfitting and underfitting with different regularization parameters.
    
    -- **Data manipulation skills covered:** Data type conversion, data transformation, horizontally stack data sets, scatter plot, data appended to lists.
    
    -- **Unsolved questions:** 1) How to properly use the BFGS optimization function in Python --- minimize(fun, x0, args = (), method = "bfgs")?   2) How to write BFGS algorithm without the use of library? 


- ### **Multi-class Classification and Neural Networks**
    
    [Lecture Slides 1](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%208.pdf)
    
    [Lecture Slides 2](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%209.pdf)
    
    [Implementation in Python --- Multi-class Classification and Neural Networks](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Multi-class%20Classification%20and%20Neural%20Networks_2.ipynb)
    
    -- **Tasks performed:** Load Matlab source file with higher dimensions, visualize the hand written digits, build a multi-class classifier using the regularized logistic regression model, feedforward propagation and prediction. 
    
    -- **Data manipulation skills covered:** Data type conversion, image display.
    
    -- **Unsolved questions:** 1) Unable to visualize higher dimensional data independently;   2) Theories relevant with forward propagation algorithm?

    [Implementation in Python --- Neural Networks Learning](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Neural%20Networks%20Learning_2.ipynb)
    
    -- **Tasks performed:** Load Matlab source file with higher dimensions, visualize the hand written digits, backpropagate algorithm to calculate the gradients, add regularization to the gradient, learning parameters by using the nonlinear conjugate gradient algorithm in the library, visualize the hidden layer.
    
    -- **Data manipulation skills covered:** Data type conversion, image display.
    
    -- **Unsolved questions:** 1) Unable to visualize higher dimensional data independently;   2) Theories relevant with backpropagate alrithm?   3) How to write conjugate gradient algorithm without the use of library?
    

- ### **Regularized Linear Regression and Bias v.s. Variance**

    [Lecture Slides](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%2010.pdf)
    
    [Implementation in Python](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Regularized%20Linear%20Regression%20and%20Bias%20v.s.%20Variance_2.ipynb)
    
    -- **Tasks performed:** Learning parameters by using BFGS algorithm in the library, plot learning curve, polynomial regression
    
    -- **Data manipulation skills covered:** Data type conversion, data transformation.
    
    -- **Unsolved questions:** How to write BFGS algorithm without the use of library?   


- ### **Support Vector Machines**

    [Lecture Slides](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%2012.pdf)
    
    [Simplified SMO Algorithms](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Simplified%20SMO%20Algorithm.pdf)
    
    [Implementation in Python](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/Support%20Vector%20Machines.ipynb)
    
    -- **Tasks performed:** Implement Sequential Minimal Optimization (SMO) algorithm to train SVM with linear kernel and visualize the linear boundary decision, implement SMO algorithm to train SVM with Gaussian kernel.
    
    -- **Data manipulation skills covered:** Data type conversion, transform, iterations.
    
    -- **Unsolved questions:** The computation of Gaussin kernel failed, because it was running forever.... How to compute Gaussin kernel efficiently and correctly? 


- ### **K-means Clustering and Principal Component Analysis**
    
    [Lecture Slides 1](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%2013.pdf)
    
    [Lecture Slides 2](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/lecture%2014.pdf)
   
    [Implementation in Python](https://github.com/lxn1021/Notes-Machine-Learning-Course-by-Andrew-Ng/blob/master/K-means%20Clustering%20and%20Principal%20Component%20Analysis.ipynb)
    
    -- **Tasks performed:** Compute centroid means, run K-means and visualize the progress, image compression with K-means, use Principal Component Analysis (PCA) to perform dimensionality reduction, project data and visualize the projection.
    
    -- **Data manipulation skills covered:** Data type conversion, data transformation, display image.
    
    -- **Unsolved questions:** 1) The mathematics behind PCA?   2) The clustering progress doesn't seem very reasonable.
