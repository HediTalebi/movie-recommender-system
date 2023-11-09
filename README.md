
# Movie Recommender System with Clustering and Gradio User Interface

With the vast amount of movies available today, it can be overwhelming for related businesses to discover new movies that align with their users' interests. Movie recommender systems play a crucial role in addressing this challenge by suggesting personalized movie recommendations based on various factors such as genre, ratings, and user preferences.

This repository presents a movie recommender system that combines the power of clustering algorithms and the versatility of the Gradio library to create an efficient and intuitive platform for users to explore and discover movies.

Explore our project and see how it works by visiting our project's Hugging Face Space at this link: https://huggingface.co/spaces/AbolfazlFekri/AbolfazlFekriHediyehTalebi_MLFinal_SBU_V1.2 ." 
## Dataset

The dataset used for this task focuses explicitly on the "movies_metadata" subset of the larger dataset. This subset contains a vast collection of information on 45,000 movies, encompassing various essential details such as budget, revenue, release dates, languages, production countries, and more. The Movies Dataset, obtained from The Movie Database (TMDb) API, is a comprehensive resource for movie-related data, allowing researchers, analysts, and developers to understand movie characteristics and trends better.

## Gradio User Interface

Gradio is a Python library that allows us to create interactive interfaces for machine-learning models. In this project, we utilized Gradio to develop an interface for our Movie Recommender System. The interface enables users to select their favorite movies or enter (type) movie names and provides recommendations based on their choices.


## Importing and Installation

To ensure the proper installation of the packages required for our Movie Recommender System on Hugging Face, we used the `requirements.txt` file for installing necessary modules. This approach ensures a consistent and reproducible setup for our project, managing dependencies effectively.

After installation, we imported libraries, including Gradio, for creating interactive interfaces, and other relevant libraries, such as requests, Images from PIL, load_dataset from datasets, etc., for the functionality and implementation of our Movie Recommender System.

## Reading Data

We created a dedicated dataset for our movie recommender system within the Hugging Face environment by uploading a CSV file containing our clustering model's output. This file included essential information about the movies, such as their titles, features, and assigned clusters. We employed the `load_dataset` function from the Hugging Face datasets module to access and utilize this dataset, transforming it into a pandas DataFrame for convenience.

## Deploying in Hugging Face

Hugging Face is a platform and community focused on natural language processing (NLP) and machine learning. We deployed our movie recommender system using Hugging Face Spaces in our project, making it easily accessible to others. The Gradio code, which powers our interactive interface, is in the `app.py` file, serving as our model in this context.

To ensure the necessary dependencies are installed, we included a section at the top of the code that installs the required packages using the `requirements.txt` file.

## Conclusion

In summary, a movie recommender system was developed using the clustering method and the Gradio user interface to provide personalized movie recommendations based on user preferences and movie features. The clustering method grouped movies based on shared characteristics, allowing for the identification of movie similarities and patterns. A user-friendly interface for seamless movie exploration and recommendation was created with the Gradio library. The system was deployed on Hugging Face Spaces, making it easily accessible to a broader audience.

Results show that recommended movies seem related to the real world, as verified through user testing and comparisons with movie websites' recommendation engines.

For more details on installation, usage, and contributing to this project, please refer to report file.
