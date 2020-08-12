# MovieGenrePrediction
The goal of this project is to build and critically analyse some supervised Machine Learning algorithms, to automatically identify the genre(s) of a movie on the basis of its audio, visual and textual (metadata) features.
## Data Set
train features.tsv: Contains features of 5240 training instances.  
train labels.tsv: Contains a single genre label for each training instance  
valid features.tsv: Contains features of 299 validation instances.  
valid labels.tsv: Contains a single genre label for each validation instance.  
test features.tsv: Contains features of 298 test instances.  
  
**Each movie in the data set is indexed with a unique movieID. We provide three different types of features.  
Details are provided in the README file, as well as the references listed under Terms of Use:**  
• Metadata features: For each movie, we provide its title, its year of release, and a list of tags (like ‘predictable’, ‘boring’, or ‘based on a book’) provided by human annotators.  
• Visual features: We provide 107 pre-computed visual features, pre-extracted from the movie trailer. Each feature has a continuous floating point value. Note that these features are not interpretable.  
• Audio features: We provide 20 pre-computed audio features capturing acoustic signals from the movie trailer. Again, each feature takes a continuous value, and the values are not interpretable.  

**Each movie is labelled with its genre, i.e., with a single label from one of 18 possible genre labels:**  
’Action’, ’Adventure’, ’Animation’, ’Children’, ’Comedy’, ’Crime’, ’Documentary’, ’Drama’, ’Fantasy’, ’Film noir’, ’Horror’, ’Musical’, ’Mystery’, ’Romance’, ’Sci fi’, ’Thriller’, ’War’, ’West-ern’  
## Source Code
This project is aimed to predict movie genre from Audio, Visual and Text Features by machine learning methods.  
There are two files for the project2,LinearModel.ipynb and NonLinearModel.ipynb  
File LinearModel.ipynb contains two linear machine learning methods(Logistic Regression and Naive Bayes) and the evaluation of methods.  
File NonLinearModel.ipynb contains one non-linear machine learning method(Neural Network).  
## Report
All results and performance of classifiers are shown in the report.
