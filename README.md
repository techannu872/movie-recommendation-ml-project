
# Movie-Recommendation-System

A personalized movie recommendation system that suggests films based on user preferences and viewing history. This project utilizes machine learning algorithms and various Python libraries to deliver tailored movie recommendations.


## Acknowledgements

Table of Contents
-  Project Description
-  Tech Stack
-  Installation
-  Deployment
-  File Structure
-  Contributing



## Project Description

The Movie Recommendation System is a web application built with Streamlit, designed to recommend movies based on user input. It fetches movie data and posters from the TMDb API and employs machine learning techniques to suggest movies similar to those the user likes.
## Tech Stack

- Python: Core programming language

- Streamlit: Web application framework

- Pandas: Data manipulation and analysis

- Scikit-learn: Machine learning library

- Requests: HTTP requests for API calls

- Pickle: Model serialization

- The Movie Database (TMDb) API: External API for movie data
## Installation


Prerequisites:-
- Python 3.x
- Git
## Deployment

1. Clone the repository:

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
  ```

2. Install required packages:

```bash
pip install -r requirements.txt

  ```
3. Download the model and data files:

```bash
[Download the model files](https://example.com/largefile.pkl) and place them in the root directory of the project.

  ```
4. Alternatively, if using Git LFS:

```bash
git lfs pull

  ```



## Usage

1. Run the application:
```bash
python -m streamlit run app.py

  ```
![WhatsApp Image 2024-08-01 at 21 24 44_b95c17e2](https://github.com/user-attachments/assets/2d28f868-fd65-4608-a831-2230002e339b)


2. Interact with the UI:

- Select a movie from the dropdown list.

-  Click the 'Recommend' button to get a list of recommended movies with posters.

-  Click on a movie poster to learn more about it.

  ![WhatsApp Image 2024-08-01 at 21 25 23_f594f9de](https://github.com/user-attachments/assets/7b3d3386-6df9-4ee4-ba3c-99e5425d2fa0)




## File Structure


```bash
movie-recommendation-system/
│
├── app.py                 # Main application file
├── movie_dict.pkl         # Serialized movie data
├── similarity.pkl         # Serialized similarity matrix
├── requirements.txt       # List of dependencies
└── README.md              # Project description and instructions

  ```
## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

- Fork the repository
- Create your feature branch (git checkout -b feature/feature-name)
- Commit your changes (git commit -m 'Add some feature')
- Push to the branch (git push origin feature/feature-name)
- Create a new Pull Request

  ## License

[MIT](https://choosealicense.com/licenses/mit/)

