# distilgpt2-followup-qg

In this project we train a language model (distilgpt2) on a small custom dataset, to generate follow-up questions for various user inputs. The model was chosen due to its small size (~82M parameters) and the speed with which it can be trained.

With the limited samples in the custom dataset, a K-Fold cross validation technique was used, dividing the entire dataset into five subsets, to ensure the model generalized well.

A few test cases has been tried out with the final trained model and it was able to perform well. For custom user input, uncomment the last cell block and run the notebook
