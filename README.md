
machine_learning
After lots and lots of fine tuning and failure, the models that stuck out as the best ended up being the neural model (model4) and the k-nearest-neighbor model (model6). While playing with all the x variables using decision tress and random forests, it became clear that the difference between including all possible variables and a select few provided negligable difference, or even worse results as variables were further limited, leading me to include all variables for other models. The K nearest neighbor model had the best spot at k = 17, which is roughly what I would have expected based on the random forest analysis.

The neural model is almost certainly the best as it was able to bring in all the variables and self tune the accuracy and weighting of each variable over many itterations to achieve a very high accuracy score with very little loss.
