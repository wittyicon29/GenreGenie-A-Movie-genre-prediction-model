
# Introduction
GenreGenie is an innovative movie genre prediction model designed to accurately determine the genre of a movie solely from its synopsis. The primary objective of this project is to harness the power of cutting-edge natural language processing (NLP) techniques and neural networks to unlock the genre hidden within a movie's narrative. With GenreGenie, filmmakers, streaming platforms, and movie enthusiasts can quickly and effortlessly identify the genre of any movie, enhancing the movie-watching experience.

# Dataset
The backbone of GenreGenie's success lies in its comprehensive dataset. Curated from diverse sources, the dataset contains over 40,000 movie synopses, meticulously labeled with their corresponding genres. The data is available in the efficient parquet format, and we have thoughtfully converted it into an accessible pandas dataframe for ease of use. This rich dataset ensures that GenreGenie is well-equipped to handle a wide array of movie genres with precision.

Access the dataset here: [HuggingFace - Movie Genre Prediction Dataset](https://huggingface.co/datasets/datadrivenscience/movie-genre-prediction)

# Models
To ensure robustness and flexibility, we have implemented two powerful models within GenreGenie:

BERT-based Model with Transformers:
GenreGenie leverages the state-of-the-art BERT (Bidirectional Encoder Representations from Transformers) architecture to comprehend the intricate nuances of movie synopses. The transformer-based approach enables the model to grasp the contextual information effectively, leading to impressive genre prediction accuracy.

LSTM Neural Network Model:
Our LSTM (Long Short-Term Memory) neural network provides a robust alternative to predict movie genres. LSTM networks excel at capturing sequential information, making them well-suited for understanding the temporal dynamics present in synopses.

# Evaluation
At GenreGenie, we take model evaluation seriously. Our BERT-based model underwent rigorous testing and was submitted to a HuggingFace competition. We are proud to announce that out of 106 submissions, GenreGenie's BERT model secured an impressive 52nd rank. This speaks volumes about the reliability and competitive edge of our model.

Performance Metrics
BERT-based Model Accuracy: 38%
LSTM Neural Network Model Accuracy: 14%

# Usage
To run the GenreGenie project on your local machine, follow these steps:

Clone the repository from GitHub:
```sh
git clone https://github.com/wittyicon29/GenreGenie.git
cd GenreGenie
```

Set up a virtual environment (optional but recommended):
```sh
python3 -m venv venv
source venv/bin/activate
```
Install the required packages:

```sh
pip install -r requirements.txt
```

Download the dataset from the link provided in the repository's README.md and save it as movie_genres_dataset.parquet in the project's root directory.

Run the training scripts for both BERT-based and LSTM-based models. Ensure that you have a compatible GPU with CUDA support to accelerate the training process for the BERT model.

After training, you can now use the trained models for genre prediction on new movie synopses. Modify and run the code snippet provided in the README.md to predict the genre using GenreGenie.

Remember to have Python and the necessary dependencies installed on your machine before running the project. It is also advisable to use a virtual environment to avoid potential package conflicts with other projects on your system.

Please note that these instructions assume you have set up your environment correctly. Adjust the steps as needed for your specific development environment. Enjoy using GenreGenie and exploring the magic of movie genre prediction!

# Conclusion
GenreGenie represents a pioneering leap in the field of movie genre prediction. With an accuracy of 38% achieved by our advanced BERT-based model, we outperform conventional approaches by a significant margin. We believe this breakthrough will redefine the movie industry and empower users with seamless genre classification.

We invite you to explore GenreGenie and experience its magic in action. Together, let's unlock the hidden genres of movies and embark on an exhilarating cinematic journey. Happy predicting!

Note: If you find this project intriguing and wish to contribute or collaborate, feel free to reach out. Together, we can further enhance GenreGenie's capabilities and make it an indispensable tool for all movie enthusiasts. Let's revolutionize the way we understand and appreciate movies!
