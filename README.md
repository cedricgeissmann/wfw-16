# Manim Playground

This is a repository to test out the manim library.

## Run with Binder

If you just want to play with the code in the noteboos, you can just run this
Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cedricgeissmann/wfw-16.git/HEAD?filepath=notebooks)

## Installation

The installation process can be found in the
[documentation](https://www.manim.community/). After installing all the
dependencies for your system, you can run the following code to setup this
repository.

```bash
python3 -m virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

After this setup the manim library should be installed in the virtual
environment, and jupyter is also installed. To work with the jupyter setup, run
the following command in your terminal `jupyter notebook`. This should launch a
new browser tab in the current directory. Navigate to notebooks and start
developing videos.
