## Setup

Activate vitualenv
```bash
source ml-housing-cali/bin/activate
pip install -r requirements.txt
```

For using a new virtualenv
```bash
virtualenv NEW_ENV
source NEW_ENV/bin/activate
pip install -r requirements.txt
```

## Utils
To download data, run this command in your notebook:
```python
fetch_housing_data()
```

and
```python
load_housing_data()
```