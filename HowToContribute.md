# How to contribute

Before starting to edit the documentation create an environment to install you software

## Create environment

    conda create --name documentation python==3.13

**documentation** is just an example, you can chose what ever you like.
Next you activate your environment and install mkdocs:

    conda activate documentation
  
    pip install mkdocs
  
    pip install mkdocs-material

now you can start and test with if everything works fine:

    mkdocs --version

If you like to look at your documentation,go to main directory, where the mkdocs.yml file is stored.

    mkdocs serve

Open http://127.0.0.1:8000/ in your browser.
