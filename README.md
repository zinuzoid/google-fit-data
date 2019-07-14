# google-fit-data
Load bulk weight/steps data to a Google Fit account

# Secrets

In the file `secret.yml` add your secrets in yaml format

ex.
```
client_id: 'YOUR CLIENT ID'
client_secret: 'YOUR CLIENT SECRET'
fitness_api_key: 'YOUR FITNESS API KEY'
redirect_uri: 'http://localhost'
project_id: 'YOUR PROJECT ID'
```

## Download and installation
```
git clone https://github.com/ryanpconnors/google-fit-data.git
cd google-fit-data
virtualenv -p /usr/bin/python2.7 venv
pip install -r requirements.txt
```

## Import weight data into Google Fit
```
python weight/import_weight_to_gfit.py
```

## Import steps data into Google Fit
```
python steps/import_steps_to_gfit.py
```
