# Course Recommendation System 

### Overview

This is a simple content-based course recommendation system built using Python and scikit-learn. The system suggests courses similar to the input course based on their skills using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.

The course recommendation system uses the skills mentioned for each course to create a feature representation using TF-IDF. It then calculates the cosine similarity between courses to find similar courses. The system recommends the top 10 courses that are most similar to the input course.

The recommendation system can be used to find courses similar to a given input course. It will prompt the user to enter a course name and provide a list of recommended courses.

### Dataset
The dataset used in this project (Coursera.csv) contains information about various courses available on Coursera, including their names, universities, difficulty levels, course ratings, course URLs, descriptions, and skills required. Dataset is available on kaggle.
