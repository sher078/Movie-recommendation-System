# Movie Recommendation System

This project utilizes Pandas, Scikit-learn, NumPy, Pickle, and Streamlit (for creating simple and elegant web applications in pure Python) to build a basic movie recommendation system. The system is designed to take an input movie from the user and recommend five similar movies from the TMDB-5000-movies dataset available on Kaggle.

## Features
- Recommends five movies similar to the input movie from the TMDB-5000-movies dataset.
- Utilizes Scikit-learn for calculating nearest neighbors for recommendation.

## Target Audience
This project is beneficial for developers and machine learning enthusiasts looking to understand and implement movie recommendation systems.

## Technical Details
- **Python Version:** 3.9.0
- **Dependencies:**
  - TensorFlow 2.10
  - Scikit-learn 1.3.0
  - NumPy
  - Pickle
  - tqdm
  - ResNet-50 model from TensorFlow
- **Additional Requirements:**
  - Two pickle files trained on the Fashion Product Images Dataset are required for the system to recommend similar images.
  - CUDA installation might be required so that TensorFlow can use the dedicated GPU (CUDA can speed up the process of pickle file generation).

## Installation and Usage
1. Download the complete folder from the drive link provided below.
2. Open the `.ipynb` file and change the path to the datasets.
3. Run the `.ipynb` file and install the required libraries.
4. Run the `app.py` file.
5. In the terminal, type:
   ```sh
   streamlit run app.py
   ```
6. A webpage will open in your browser where you can enter a movie existing in the dataset and click on **Recommend** to get recommendations.

   ![Streamlit App Running](./image.png)

   ![Movie Recommendation Web App](./image2.png)

## Additional Information
### Links and Resources
- **Movies Dataset on Kaggle:** [Link to Dataset](https://www.kaggle.com/)
- **Google Drive for Required Pickle Files:** Google Drive (You might need to generate `Filenames.pkl` file again to make the project work.)

## Future Plans
Future updates may include:
- Optimization of recommendation algorithms.
- Support for more movies in the dataset.
- Integration with mobile applications for user-friendly interactions and hosting the web application.

