# docs

Personal notes on developing tools and programming languages.

# Python

1. Installing python:
    1. Usually good to search for "Setting up python development environment in [Mac/Windows]" and follow instructions.
    
1. Set-up with virtual environments:
    1. Create a folder for your project.
    1. Open the folder in Visual Studio Code (VS).
    1. Open the terminal in VS and run the following.  This step only needs to happen once per project.
    ```
    python3 -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    ```
    4. Search for "Select Python Interpreter" VS and select `.venv`. This will ensure you don't mess with the baseline python installation in your computer.
    5. To install packages, run `pip install ...` from the terminal in VS.  Make sure the virtual environment is active before: there should be a `(.venv)` in the terminal.

1. [The Python Tutorial](https://docs.python.org/3/tutorial/index.html):
    1. Getting started: Chapters 3, 4 and 5.
    1. Really useful afterwards: 8 and 9.
    
1. Data handling: [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html).
    1. Worth going through the [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html) chapter.
    1. Otherwise, browse as needed.
    
1. Useful libraries and tools:
    1. `os` to look for folders, environment variables and manage files.
    1. `requests` to interact with webpages and APIs.
    1. `altair` for charts and plots in python ([docs](https://altair-viz.github.io/))
    1. `streamlit` for interactive dashboards ([docs](https://docs.streamlit.io/))
    1. String formatting: https://docs.python.org/3/tutorial/inputoutput.html
