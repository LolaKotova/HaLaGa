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

Later if you like to publish the finished pages:

    mkdocs gh-deploy


## Structure of the documentation

In your home directory is the file which contains the document structure
    
    mkdocs.yml

if you change the name or directoryname of your *.md files, make sure, you also change it in mkdocs.yml

In this case we changed the design a little bit, so we need
    
    stylesheets/extra.css

All your individual directories and files nied to be stored in the directory 
    
    docs
