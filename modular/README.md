# Going Modular Scripts

The Python scripts in this directory were generated to help training.

They breakdown as follows: 
* `data_setup.py` - a file to prepare and download data if needed.
* `engine.py` - a file containing various training functions.
* `model_builder.py` - a file to create a PyTorch TinyVGG model.
* `train.py` - a file to leverage all other files and train a target PyTorch model.
* `utils.py` - a file dedicated to helpful utility functions.
* **Extra:** `predictions.py` - a file for making predictions with a trained PyTorch model and input image