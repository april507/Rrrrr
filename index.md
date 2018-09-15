## Welcome to my learning on machine learning

This is a place for me to build hypothesis, do experiments, and record my learnings using various datasets. 

*****
### Projects 

* [Customer churn project](https://april507.github.io/Rrrrr/projects/churn/main.nb.html)
* [Bike sharing project](https://april507.github.io/Rrrrr/projects/bike_sharing/main.nb.html)

*****
### General Guideline

* When making decisions, keep in mind trade-offs between speed, explainability, simplicity, performance, and more

*****
### Logistic Regression

* L1, L2, normalization
    + L1 lasso regression (`glmnet alpha==1`), sparse variables
    + L2 ridge regression (`glmnet alpha==0`), smaller coeff, less sensitive to outliers
* Caret package allows mixing L1 & L2 regularization, want to know if different lambdas can be used in the mixture

*****
### Number of folds experiment

* Number of folds don't impact model results very much, especially on datasets with large number of rows
* Results may be unstable when a very small fold is used (<4) 

*****
### Support or Contact

You can use the [editor on GitHub](https://github.com/april507/Rrrrr/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
