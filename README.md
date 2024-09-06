# Toxic Word Prediction

This project aims to predict toxic words using two different machine learning models: a **Naive Bayes (Generative)** model and a **Random Forest (Discriminative)** model. The project demonstrates the effectiveness of both models in identifying toxic words from the dataset after preprocessing and training.

## Project Structure

- **`models/`**: Contains the saved machine learning models.
  - **`model_dis/`**: Contains the saved Naive Bayes model.
  - **`modes_dis/`**: Contains the saved Random Forest model.
  
- **`text_analysis_final.ipynb`**: The Jupyter notebook file that contains all the preprocessing, model training, and prediction code. Running this notebook will execute the complete toxic word prediction workflow.

## Models Used

1. **Naive Bayes Model (Generative Approach)**:
   - This model uses the generative approach to classify the text as toxic or non-toxic.
   - The model was trained and saved in the `models/model_dis/` folder.

2. **Random Forest Model (Discriminative Approach)**:
   - A discriminative machine learning model that uses Random Forest to classify the text.
   - The model was trained and saved in the `models/modes_dis/` folder.

## Steps to Run

1. **Pre-requisites**:
   - Ensure you have Python installed along with the necessary libraries.
   - The libraries required include but are not limited to:
     - `scikit-learn`
     - `numpy`
     - `pandas`
     - `nltk`
     - `matplotlib`
   
2. **Running the Project**:
   - Simply open and run the `text_analysis_final.ipynb` notebook.
   - This notebook performs the following:
     - Preprocessing of the dataset (cleaning, tokenization, etc.).
     - Training the **Naive Bayes** and **Random Forest** models.
     - Saving the trained models in their respective directories.
     - Making predictions using the trained models.
   
3. **Model Outputs**:
   - After running the notebook, the models will predict whether a word is toxic or non-toxic based on the trained data.
   
## File Descriptions

- **`text_analysis_final.ipynb`**: Main notebook that handles data preprocessing, training the models, saving the models, and prediction generation.
- **`models/model_dis/`**: Directory containing the trained **Naive Bayes** model.
- **`models/modes_dis/`**: Directory containing the trained **Random Forest** model.

## Conclusion

This project demonstrates how two different machine learning models—**Naive Bayes** and **Random Forest**—can be used to classify toxic words. By running the provided Jupyter notebook, you can reproduce the entire training and prediction process.
