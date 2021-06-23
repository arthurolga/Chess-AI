# ♟ Chess AI

Project created with MLOps-Template cookiecutter. For more info: https://mlop-guide.github.io/


## 📋 Requirements

* DVC
* Python3, pip and jupyter
* GPU Access OR Google Colab
* Access to ChessAI Google Drive OR the following files:
    - data/dataset.7z
    - models/model-ResConv2d.h5

## 🏃🏻 Running Project

Running the playable Jupyter Notebook
```
jupyter notebook notebooks/play.ipynb
```

### ✅ Pre-commit Testings

In order to activate pre-commit testing you need ```pre-commit```

Installing pre-commit with pip
```
pip install pre-commit
```

Installing pre-commit on your local repository. Keep in mind this creates a Github Hook.
```
pre-commit install
```

Now everytime you make a commit, it will run some tests defined on ```.pre-commit-config.yaml``` before allowing your commit.

**Example**
```
$ git commit -m "Example commit"

black....................................................................Passed
pytest-check.............................................................Passed
```
