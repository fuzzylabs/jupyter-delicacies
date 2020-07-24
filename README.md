# Introduction

[Jupyter](https://jupyter.org) notebooks are a way of sharing executable experiments. They're widely used as standard in data science and machine learning, as well as being used more broadly for education, documentation and experimentation. This is a collection of notebooks on assorted topics in artificial intelligence, computer science and mathematics.

The notebooks are mainly in Python but other programming languages may be used as well.

# Contents

## Computer Vision

| Link                    | Description                                                                                                |   |
|-------------------------|------------------------------------------------------------------------------------------------------------|---|
| [OCR](vision/ocr.ipynb)   | Comparing different modes of Tesseract OCR and Google Vision API models for text detection and recognition | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fuzzylabs/jupyter-delicacies/blob/master/vision/ocr.ipynb) |

# Running

## Prerequisites

* Python 3
* Virtualenv
* Pip

## Running for the first time

You'll need to set up Virtualenv (this is optional but it makes it easier to manage Python dependencies) and install the dependencies. Once you've checked out the repository, run these commands in the root directory:

**n.b. Depending on how Python is configured on your system it might be named `python` or `python3`. Same goes for `pip`/`pip3`** 

```sh
python3 -m venv env
env/bin/activate
pip3 install -r requirements.txt
```

Virtualenv creates an `env` directory where Python dependencies for the project will be stored. This directory is ignored in Git.

Now you can start Jupyter by running `jupyter notebook`. This should open a tab in your web browser allowing you to browse Jupyter files, but if not then you can try visiting `http://localhost:8888`.

## Running after the first time

If you've already set up Virtualenv and installed dependencies then you can reactivate the virtual environment at any point by running `env/bin/activate`.

# Emacs

Instead of using Jupyter in the browser you can embed it directly into everybody's favourite text editor. There are a couple of approaches to doing this, but we'll stick with the [Emacs Ipython Notebook](http://millejoh.github.io/emacs-ipython-notebook) extension. After following the installation instructions on the website you'll be ready to either:

* Run a Jupyter process within Emacs with `M-x run`
* Connect to an existing Jupyter process with `M-x login`

The latter is potentially a safer option.

# Other interesting notebook collections

* [Machine learning with Python](https://github.com/tirthajyoti/Machine-Learning-with-Python)
