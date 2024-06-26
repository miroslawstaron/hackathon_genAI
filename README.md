# hackathon_genAI
Hackathon to create, train and use generative AI models in software engineering tasks.

## Goals
The main goal of this hackathon is to create awareness of the potential of generative AI models in software engineering tasks. The participants will be able to create, train and use generative AI models in software engineering tasks.

We use Hugging Face's transformers library to create, train and use generative AI models. The library is very well documented and has a large community of users and contributors. It is also relatively easy to use and to modify.

## Before the hackathon
Before attending the hackathon, you need to prepare your environment for it. What you need is:

1. Python environment -- Python 3.11 is recommended, because it is not the latest one, but relatively new so still supported. You can use any Python environment you like, but I recommend using pyenv to manage your Python versions.


If you are using MS Windows as an operating system, I recommend to use WSL2 to execute your scipts. Here is a guide to install WSL2: https://docs.microsoft.com/en-us/windows/wsl/install.

In WSL2, the default Python version is 3.8.10, so you will need to install Python 3.11.0. Here is a guide to install Python 3.11.0 in WSL2: https://computingforgeeks.com/how-to-install-python-on-ubuntu-linux/?utm_content=cmp-true.

Once the python is installed, create a virtual environment with the following command:

```python3.11 -m venv /some_place_on_your_drive/hackathon_genAI```

If you get into problems with installing the venv and the right python version, please take a look here: https://stackoverflow.com/questions/70422866/how-to-create-a-venv-with-a-different-python-version 

2. Set up the Python environment -- activate the virtual environment and install the required packages:

```source /some_place_on_your_drive/hackathon_genAI/bin/activate``` 

Your prompt should change to something that starts with (hackathon_genAI). Then install the required packages:

```pip install -r requirements.txt```

3. Go to the folder `before` and open up the `start.ipynb` notebook. Follow the instructions in the notebook to prepare your environment for the hackathon.

## During the hackathon
During the hackathon, we will work on the following tasks:
1. Code similarity -- developing a tool that can help us find security vulnerabilities in the code.
2. Code completion -- developing a tool that can help us write code faster.
3. Code summarization -- developing a tool that can help us understand the code better.
4. Model training -- training an own model which we can use even to solve tasks 1-3. This task requires a more powerful laptop or a GPU. 

## After the hackathon

