# Setup 

Follow these setup steps to prepare to run the Mistral fine tuning [blog post.](https://brev.dev/blog/fine-tuning-mistral) This should run on any *nix systems such as WSL2. (Note: Created using Python 3.9.12.)

This project uses virtual env to isolate a python environment and pulls all necessary requirments from a requirements-file. 

## Setup Instructions 

```bash
# Create a virtual environment using venv (do this *inside* of the project directory)
python -m venv env

# Activate your environment
source ./env/bin/activate 

# Verify that you have a "(env)" next to your command prompt. You can deactivte the virtual environment later by running `deactivate`

# Install dependencies (NOTE: this loads more than is strictly required for this demo)

python -m pip install -r requirements.txt

#The `python -m` part ensures that you run your virtual environment's pip and not the global pip.
```

You can now run the finetune.ipynb. (If you are running on VS Code don't forget to connect it to your virtual environment) 
