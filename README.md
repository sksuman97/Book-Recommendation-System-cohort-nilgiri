# BOOK RECOMMENDATION SYSTEM
These project is part of the “Machine Learning &Advanced Machine Learning” curriculum as capstone projects at [AlmaBetter](https://www.almabetter.com/). 

#### -- Project Status: [Completed]

## Objective<br>
The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge
amount of income when they are efficient or also be a way to stand out significantly from competitors. 
![image](https://user-images.githubusercontent.com/64405940/120105598-3b97b880-c177-11eb-988e-32f5bcab6dad.png)



### Methods Used
* Descriptive Statistics
* Data Visualization
* Machine Learning


### Technologies
* Python
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn
* Surprise

### Data
The Book-Crossing dataset comprises 3 files.
* Users : 
Contains the users. Note that user IDs (User-ID) have been anonymized and map to
integers. Demographic data is provided (Location, Age) if available. Otherwise, these
fields contain NULL values.
* Books : 
Books are identified by their respective ISBN. Invalid ISBNs have already been removed
from the dataset. Moreover, some content-based information is given (Book-Title,
Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web
Services. Note that in the case of several authors, only the first is provided. URLs linking
to cover images are also given, appearing in three different flavors (Image-URL-S,
Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the
Amazon website.
* Ratings :
Contains the book rating information. Ratings (Book-Rating) are either explicit,
expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,
expressed by 0.

## Project Description
* EDA - Performed exploratory data analysis on numerical and categorical data.
* Data Cleaning - Missing value imputation,Outlier Treaatment
* Feature Selection - Used User-ID,ISBN and Books-Rating for model development.
* Model development - Tried Popularity based model and Collaborative filtering (Both Memory based and Model based).


## Needs of this project

- data exploration
- data processing/cleaning
- recommendation system developer

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data 
* Users_data is being kept [here](https://github.com/Harsh1091996/Book-Recommendation-System/blob/main/Users.csv) within this repo.
* Ratings_data is being kept [here](https://github.com/Harsh1091996/Book-Recommendation-System/blob/main/Ratings.csv) within this repo.
* Books_data is being kept [here](https://drive.google.com/file/d/1phmZ4_TzhGi40dPPU_bN_Mz8Bxlhe4d9/view?usp=sharing) 
    
3. Complete notebook containing Data exploration/Data processing/transformation/model development is being kept [here](https://github.com/Harsh1091996/Book-Recommendation-System/blob/cb7aab70db7b7effe4457e66c2fc26b6e85f64c4/Book_Recommendation_System.ipynb)
 
## SVD
Mathematics behind SVD
For a m × n matrix(M) there exists a singular value decomposition of M, of the form

Singular value decomposition
where
U is a m × m unitary matrix. (left singular vector)
Σ is a m × n diagonal matrix with non-negative real numbers.
V is a n × n unitary matrix . ( right singular vector)
V* is the conjugate transpose of the n × n unitary matrix.
The diagonal values of Σ are known as Singular values of M.
Conjugate Transpose: The conjugate transpose of a matrix interchanges the row and column index for each element.
Identity matrix: It is a square matrix in which all the elements of the principal diagonal are ones and all other elements are zeros.
Diagonal Matrix: It is a matrix in which the entries outside the main diagonal are all zero.
Unitary matrix: Matrices whose conjugate transpose is also its inverse, that is UU*=I.
Singular Values: Basically it denotes the square root of the eigenvalues of XX* where X is a matrix.
# Credits
Sumanta | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumanta97/ )
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sksuman97/)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@sumanta-skm98)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/file/d/1DkZqmtw2c_I-EEAOw9iyzd-EAeBoJ6nj/view?usp=sharing)


Contact me for Data Science Project Collaborations
# References
SVD- https://en.wikipedia.org/wiki/Singular_value_decomposition

