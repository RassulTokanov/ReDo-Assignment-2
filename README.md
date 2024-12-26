# ReDo-Assignment-2

# Summary of Results:

The model was trained for 20 epochs with the goal of minimizing the loss function (loss) and improving the intersection-over-union metric (io_u). During training, the validation loss (val_loss) improved multiple times, and the best model weights were saved. The final SiBaTrAcc score was 0.817, indicating successful training but with room for further improvement.

# List of Completed Steps:

1. Trained the model for 20 epochs.
2. Implemented saving of the best weights based on the minimum val_loss.
3. Achieved improvements in val_loss during the following epochs:
Epoch 1: val_loss decreased from inf to 1.0491.
Epoch 2: val_loss decreased to 0.9007.
Epoch 3: val_loss decreased to 0.7302.
Epoch 11: val_loss decreased to 0.6746.
Epoch 12: val_loss decreased to 0.6523.
Epoch 14: val_loss decreased to 0.6513.
Epoch 18: val_loss decreased to 0.6468.
4. Performed validation and saved predictions.
5. Implemented visualization of results through "clip visualization."
6. Calculated the final SiBaTrAcc metric, which scored 0.817.

This indicates progress in training the model, although some instability was observed, requiring further analysis of the data and hyperparameters.
