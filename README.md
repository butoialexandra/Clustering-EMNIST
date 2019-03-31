# COM3240: Adaptive Intelligence 
### Assignment 1: Unsupervised Learning
#### Alexandra-Cristina Butoi

The file "Assignment1.ipynb" contains all the code required in order the reproduce the results from the report. 
There are several steps that must be followed, indicated the sub-headings in the notebook:

1. Import libraries: Run the cell that imports libraries.
2. Load the datset: Run the cell that loads the datset and get the dimensions of the dataset matrix. Optionally, print the dimensions (n,m).
3. Data normalisation: The cell containing the function "normalise_data" must be run, then the function must be called on the training set.
4. Display a character from the dataset (Optional): Run the cell containing the "show_letter" function then call the function on a random index from the training set.
5. Initialise hyperparameters: The counter array must be reintialised for every run of the algorithm. The hyperparamters (eta, leaky eta, number of digits, etc.) can be adjusted for different experiments.
6. Initialise weights: Run either the cell containing the function "init_random_weights" or "init_weights_from_data", depending on whether the weights are initialised with random numbers of radnom samples from the training data. Then call the chosen function by running the appropriate cell. Optionally, you can check whether the weights matrix is normalised.
7. Display prototypes before training (Optional)
8. Training: Run a single training cell. Each of them corresponds to a different configuration, as suggested by their description from the notebook. 
9. Display prototypes after training
10. Detect dead units: Run the cell containing the function "get_dead_units_percentage" and call the function with the counter array as a parameter. Optionally, plot the distribution of winning neurons.
11. Plot the weight change over time
12. Correlation between prototypes: Run all the cells in this section in order to get a list of pairs of prototypes that are highly correlated. 
