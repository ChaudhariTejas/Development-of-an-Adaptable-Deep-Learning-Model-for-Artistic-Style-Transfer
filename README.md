# Development-of-an-Adaptable-Deep-Learning-Model-for-Artistic-Style-Transfer
Convolutional neural networks for artistic style transfer
This repository contains (TensorFlow and Keras) code that goes along with a related blog post and talk (PDF). Together, they act as a systematic look at convolutional neural networks from theory to practice, using artistic style transfer as a motivating example. The blog post provides context and covers the underlying theory, while working through the Jupyter notebooks in this repository offers a more hands-on learning experience.

If you have any questions about any of this stuff, feel free to open an issue or tweet at me: @copingbear.

Setup
Install Python (2.7), pip and virtualenv on your machine. The instructions to do this depend on your operating system (Linux, macOS, Windows), but there are many tutorials on the internet that should help you get started.

Once you have the above setup, it is quite easy to setup the requirements for the notebooks in this repository. First you clone a copy of this repository:

git clone https://github.com/hnarayanan/artistic-style-transfer.git
Then you navigate to this folder in your shell and then install the requirements needed for the Jupyter notebooks.

cd artistic-style-transfer
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
If it doesn't exist, create a file called ~/.keras/keras.json and make sure it looks like the following:

{
    "image_dim_ordering": "tf",
    "epsilon": 1e-07,
    "floatx": "float32",
    "backend": "tensorflow"
}
That's it! You can now start Jupyter and browse, open, run and modify the notebooks.

jupyter notebook
