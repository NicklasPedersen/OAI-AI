# OAI-AI

To use this project you must install the following packages via pip

```shell
pip install fuzzywuzzy
pip install mysql.connector
```

You must also create a JSON file named "dataconfig.json" with the following signature

```json
{
    "host": "<hostname/ip address>",
    "user": "<username to access db>",
    "password": "<password to access db>",
    "database": "<which database to log into>"
}
```

To run it simply do

```shell
python oai.py
```
