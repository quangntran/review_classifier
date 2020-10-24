# NLP and SVM to Classify RottenTomatoes Reviews

This project explores text classification. Since I really love The Godfather II, I decided to use its reviews for this project. 

1. I wrote a script to automate scraping reviews of a movie from [rottentomatoes.com](rottentomatoes.com) and put them into a dataset. The script took several hours to compile a data set of 20K reviews (see the file `rottentomato.csv` for the data). 
2. I also implemented Support Vector Machine (SVM) using CVXPY package and apply it to text classification. 
3. Finally, I compared to show that my version of SVM works perfectly as its results are the same as those from the `scikit-learn` package.
