# Data Analytics Course
## Description
Crash course on data analytics (or data science) for students planning to become interns and junior specialists. Course is heavily impacted by author's subjective opinions and work experience.
**Topics:**
- Data Structures in Python
- *Numpy, Pandas*, basics of dataviz
- Testing, Logging, CLI
- Packages, Modules, Import system
- Generators, Map Reduce, working with large data
- SQL
- Probability theory
- Statistical tests and A/B
- Applied statistics with *scipy.stats*
- Metric design
- Case studies
- Basic ML with *scikit-learn* and *Catboost*
- Inference of DL models for image / text processing
- Grokking algorithms interview
- Grokking analytics case interview

## How to setup
- Clone repository to local machine
- Install Pyenv using [this guide](https://github.com/pyenv/pyenv#installation)
- Install Python, used in project
  ```bash
  $ pyenv install 3.10.6
  ```
  If any problems happen - this [guide](https://github.com/pyenv/pyenv/wiki/Common-build-problems) can help.
- Create virtual environment for Python in repo
  ```bash
  $ cd <path to cloned repo>
  $ ~/.pyenv/versions/3.10.6/bin/python -m venv data_env
  ```
- Activate venv (will be active until you clode the terminal session or use `deactivate`)
  ```bash
  $ source data_env/bin/activate
  ```  
  In terminal you will now have a prefix:
  ```bash
  (data_env)$ ...
  ```

- Check everything is correct and `python` and `pip` lead to `data_env`
    ```bash
    (data_env)$ which python
    <path to repo>/nums_env/bin/python
    (data_env)$ which pip
    <path to repo>/nums_env/bin/pip
    ```
- Install dependencies using requirements.txt
  ```bash
  (data_env)$ pip install --upgrade -r requirements.txt
  ```
And you are perfect, congratulations!

## Lectures
To run the lectures, you need to use classical jupyter notebook interface with RISE package installed.

You can launch it via console:
```bash
(data_env)$ jupyter notebook
```
After that you will have a slideshow button in upper panel and slideshow option in cell parameters.
