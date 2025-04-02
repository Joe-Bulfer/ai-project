# ai-project
Github limits 25 MB max file upload. Of the 3 million lines of our [dateset](https://www.kaggle.com/datasets/masterdatasan/lung-cancer-mortality-datasets-v2/data?select=lung_cancer_mortality_data_test_v2.csv), the first 200,000 lines were extracted using the `head` command.

This may or may not be migrated to Google Collab.

Here is some notes of commands I used to get a working environment.

Link to [uv package manager](https://github.com/astral-sh/uv)

```
pip install uv (install the best package manager/project and virtual environment manager, best as in my opinion)
uv venv (create hidden .venv directory)
uv pip install scikit-learn (could add to pyproject.toml with `uv install x`)
```
