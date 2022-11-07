
# Project on National Innovation Documentation
## Instructions to Replicate Local Environment of PINS Documentation
Grab a fresh copy of the Github repository by cloning it.
`git clone https://github.com/def-community/pins-docs`

Move your directory into the repository.
`cd pins-docs`

This is not nessecary but recommended that you create a python virtual environment so installing these depencies install it for the repository folder not your entire environment. `python3 -m venv env`. You will then want to activate the environment. `source ./env/bin/activate`.

Now that we have our language environment setup and we checked out the latest branch we will want to install MkDocs, Mkdocs Material Theme and the plugins nessecary to build. I set a personal token for DEF to use to clone the `mkdocs-material-insiders` repository. Set this by running.

`GH_TOKEN=****` contact William Crum or Jer MkCoy for Token

We will then want to install all of the depencies. You can do that by running.
`pip install git+https://${GH_TOKEN}@github.com/squidfunk/mkdocs-material-insiders.git` and then `pip install -r requirements.txt`.

You are all done! Just go ahead and serve the documentation by running `mkdocs serve`.

### Important Files
`/mkdocs.yml`
	- The `mkdocs.yml` file is a configuration file that specifies several parts of the entire documentation. From configuring the navigation bar to where assets are, to the linked Github repository. See [Configuration - MkDocs](https://www.mkdocs.org/user-guide/configuration/) for MkDocs config.
	
`/docs/*.md`
	- Every single file and folder under `/docs` is the prime components and structure of the documentation. Every single `*.md` page is what gets compiled into the website. See [Configuration - MkDocs](https://www.mkdocs.org/user-guide/configuration/) for MkDocs config.
	
`/docs/stylesheets/*.css`
	- Anything within this directory is added to every single compiled page. This is how anyone can interact and create custom styling components. See [CSS First Setps - Mozzila](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps) for more information to learn CSS.
	
`/docs/overrides`
	- Within `/docs/overrides` you will see multiple `*.html` files. These HTML files extend the basic capability of what MkDocs and Mkdocs Material can provide. See [Customizing your Theme - MkDocs](https://www.mkdocs.org/user-guide/customizing-your-theme/) for more information on extending base Mkdocs features.
	
`/requirements.txt`
	- Every line within `requirements.txt` is a Python depency. Every depency is corellated to a build process for MkDocs. See [Requirment Specifiers - pypa.io](https://pip.pypa.io/en/stable/reference/requirement-specifiers/)

### Extra Documentation
[MkDocs](https://www.mkdocs.org/)
[MkDocs Material Theme](https://squidfunk.github.io/mkdocs-material/)
[About Git](https://docs.github.com/en/get-started/using-git/about-git)
[Creation of virtual environments](https://docs.python.org/3/library/venv.html)
