# Essay Quality Prediction with Keystroke Analysis 📝💻

Welcome to the Essay Quality Prediction project, where we delve into the fascinating realm of typing behavior to predict the quality of essays! 🚀

## Introduction

This repository houses a machine learning model that harnesses the power of keystroke analysis to predict the quality of essays. By extracting insights from users' typing behaviors during the writing process, our model aims to provide a unique perspective on the art of essay composition.

## Dataset 📊

The dataset comprises approximately 5000 logs of user inputs, including keystrokes and mouse clicks, recorded during the creation of essays. Each essay is scored on a scale of 0 to 6. The challenge is to predict the score an essay received based on its log of user inputs.

## Features 🧐

Our model leverages a variety of typing behavior features, including:

- Total number of activities
- Total and average action time
- Maximum word count
- Number of unique text changes
- Average cursor position

## Model Architecture 🤖

The model is constructed using a Random Forest Regressor with 100 estimators. We chose this ensemble learning technique for its robustness and ability to handle complex relationships within the data.

## Acknowledgments 🙌

We extend our gratitude to Vanderbilt University, the competition host, and The Learning Agency Lab, the independent nonprofit based in Arizona. Their support has been instrumental in fostering cross-disciplinary research with global impact.

## Usage 🚀

1. **Data Preprocessing and Feature Engineering**: Load the training data, merge logs and scores, and engineer typing behavior features.
2. **Model Training**: Utilize a Random Forest Regressor to train the model on the prepared dataset.
3. **Evaluation**: Assess the model's performance using Mean Squared Error on the validation set.
4. **Prediction**: Deploy the trained model to make predictions on the test set and create a submission file.

## Visualizations 📈

Explore the relationships between typing behavior features and essay scores through captivating visualizations:

- Scatter plots depicting the influence of activities, action time, word count, text changes, and cursor position on essay scores.
- A residual plot offering insights into prediction errors.
- A feature importance plot showcasing the significance of different features.
- A histogram illustrating the distribution of predicted scores.

## Dependencies 🛠️

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Results 📊

- Mean Squared Error on Validation Set: 0.42

## Connect with Me 🌐

Let's connect and collaborate! Feel free to reach out to me on:

- **LinkedIn**: [Vidhi Waghela](https://www.linkedin.com/in/vidhi-waghela-434663198/)
- **Kaggle**: [Vidhi Kishor Waghela](https://www.kaggle.com/vidhikishorwaghela)
- **GitHub**: [Vidhi1290](https://github.com/Vidhi1290)

I'm always open to discussions, collaborations, and learning new things together. Don't hesitate to drop me a message or explore my other projects on GitHub. Happy coding! 🚀


Feel free to dive into the code, experiment with the features, and explore the nuances of writing quality prediction through keystroke analysis! 🕵️‍♂️💬

Happy coding! 🚀
