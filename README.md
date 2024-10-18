# cnn-cat-vs-dog-classifier
This project uses a convolutional neural network (CNN) with the EfficientNetB0 architecture to classify images of cats and dogs. The model is trained on the Dogs vs Cats dataset from Kaggle, and data augmentation techniques are applied to enhance performance and improve robustness.

The data used for this project:

https://www.kaggle.com/datasets/salader/dogs-vs-cats/data

## How to Set Up Kaggle API
1. Go to your Kaggle account, and navigate to 'Account' settings.
2. Scroll down to the 'API' section and click 'Create New API Token'. A `kaggle.json` file will be downloaded.
3. Place the `kaggle.json` file in the appropriate directory:
   - For Linux or Mac: `~/.kaggle/kaggle.json`
   - For Windows: `C:\Users\<YourUsername>\.kaggle\kaggle.json`
4. Run the following commands in the notebook to set up the Kaggle API:
   `
   !mkdir -p ~/.kaggle
   !cp kaggle.json ~/.kaggle/
   !chmod 600 ~/.kaggle/kaggle.json
   `
