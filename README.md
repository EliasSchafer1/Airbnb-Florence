# Airbnb Florence

Data Science project exploring which Airbnb listing characteristics are associated with price differences in Florence, using linear regression

## Research Question

Which Airbnb listing characteristics are associated with price differences in Florence?

## Requirements

- Python 3.11+
- Poetry

## Setup

### 1. Clone repository:
```
git clone https://github.com/EliasSchafer1/Airbnb-Florence.git
cd Airbnb-Florence
```

### 2. Set up the python version (e.g. via pyenv): 
```
pyenv install 3.11.8
pyenv local 3.11.8
```

### 3. Install dependencies:
```
poetry install
poetry run nbstripout --install
```

The second command activates a Git filter that strips notebook outputs before committing, keeping diffs readable.

### 4. Run notebooks:

You can either run notebooks directly in you IDE or start JupyterLab:

```
poetry run jupyter lab
```

## Data

The dataset contains Airbnb listings in Florence, scraped on September 22, 2025. It was obtained from Inside Airbnb (http://insideairbnb.com) in April 2026.
