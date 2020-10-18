<h1 align="center">
  English Accent Detection
  <br>
</h1>

<h4 align="center"> A CNN model that uses MFCCs from the wav files to train, test & predict the native language of the speaker. </h4>

<p align="center">
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-Language-informational?style=flat&logo=python&logoColor=blue&color=blueviolet">
  </a>
  <a href="https://www.tensorflow.org/install">
    <img src="https://img.shields.io/badge/Tensorflow-Library-informational?style=flat&logo=tensorflow&logoColor=blue&color=blueviolet">
  </a>
  <a href="https://www.microsoft.com/en-au/software-download/windows10">
    <img src="https://img.shields.io/badge/Windows-OS-informational?style=flat&logo=windows&logoColor=green&color=orange">
  </a>
  <a href="https://www.jetbrains.com/pycharm/">
    <img src="https://img.shields.io/badge/PyCharm-Editor-informational?style=flat&logo=pycharm&logoColor=yellow&color=red">
  </a>
</p>

<p align="center">
  <a href="#bomb-Setup--Requirements">Setup & Requirements</a> •
  <a href="#scroll-Folder-Structure--Code">Folder Structure & Code</a> •
  <a href="#star2-Running-The-Project">Running The Project</a>
</p>

## :bomb: Setup & Requirements

### :space_invader: Editor & Environment Setup
* Install <code>Miniconda or Anaconda</code>
* Install <code>PyCharm</code>
* Open <code>PyCharm</code> and hit <code>New Project</code>
* In the <code>Create Project</code> window, select <code>`New environment using Conda`</code> and <code>`Python version: 3.8`</code>
* Hit <code>Create</code>

### :mortar_board: Requirements
After creating, the project will open. From the bottom, click on <code>Terminal</code>. Then:
* <code>conda install numba</code>
* <code>pip install librosa</code>
* <code>pip install matplotlib</code>
* <code>pip install --upgrade pip</code>
* <code>pip install tensorflow</code>
* <code>pip install easygui</code>

## :scroll: Folder Structure & Code
* Copy and paste all three <code>Python</code> scripts from this repository to the <code>PyCharm</code> project folder you just created
* Copy and paste the folder <code>Full Dataset wav</code> from this [link](https://drive.google.com/drive/folders/115Ke1X5BEkvP26g8k77dlgO-_tR7vQGg?usp=sharing) to the same <code>PyCharm</code> project folder

## :star2: Running The Project
* Use <code>Alt+Shift+F10</code> from inside <code>PyCharm</code> to run each file in the following order
* Run <code>prepare_dataset.py</code> to preprocess the dataset and create a <code>json</code> file with all processed data
* Run <code>cnn_train_test.py</code> to train the CNN model and save it
* Run <code>predict.py</code> to load the saved CNN model and use it to classify any <code>wav</code> file selected using the file explorer
