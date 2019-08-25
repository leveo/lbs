# myrepo
[![CircleCI](https://circleci.com/gh/leveo/lbs)

This is the labor statistics project. In this project, I will use python to create a machine learning to analyze labor statistic dataset which is a part of Google bigquery public data: https://console.cloud.google.com/marketplace/details/bls-public-data/bureau-of-labor-statistics?filter=solution-type:dataset&id=e632a715-857e-4c41-8257-da123607ea89

A few things to do with this project:

* install software: ```make install```
* test code: ```make test```
* lint code: ```make lint```
* run commandline tool:  

```bash
./cli.py --name john 
john-apple
```

* run jupyter notebook:

```
jupyter notebook notebook.ipynb
```

* test jupyter notebook:

```
python -m pytest --nbval notebook.ipynb
```
