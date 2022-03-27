# Module 13 Challenge
Module 13 challenge repository containing a model to predict whether applicants will be successful if funded by Alphabet Soup, a venture capital firm, based on a variety of categorical and numerical features. Initially a sequential model with two dense hidden layers was created and assessed. Then, potential optimization was evaluated by creating two similar alternative models:

1. A third dense layer was added
2. More hidden nodes were used

The original model had the best accuracy score of the three. The second alternative had very similar accuracy but higher loss. Full results are below and can also be found in the jupyter notebook.

* Original - Loss: 0.591, Accuracy: 0.727
* Alternative #1 - Loss: 0.599, Accuracy: 0.704
* Alternative #2 - Loss: Loss: 0.630, Accuracy: 0.725

## Technologies

This project leverages Python 3.7 in Jupyter Lab with the following packages:

* [pandas](https://pandas.pydata.org/) - For financial data analysis tools
* [numpy](https://numpy.org/) - For numerical functions to aid in financial calculations
* [scikit-learn](https://scikit-learn.org/stable/user_guide.html) - To create models for fitting data and making predictions
* [tensorflow](https://www.tensorflow.org/) - To build, deploy and assess machine learning models

## Contributors

Starter code for this app was provided by the GWU Fintech Bootcamp program. Updates to that code to fulfill the analysis were done by Peter Lefebvre (peter.c.lefebvre@gmail.com).

## License

[MIT License](https://github.com/plefebvre1/module_13_challenge/blob/main/LICENSE)
