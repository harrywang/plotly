Register an account on ploy.ly and get username and API key.

Setup
```
virtualenv -p /user/bin/python2.7 venv
source venv/bin/activate
pip install -r requirement.txt
python -c "import plotly; plotly.tools.set_credentials_file(username='YourUsername', api_key='YourAPIKey')"
```


If having trouble with matplotlib, try http://stackoverflow.com/questions/21784641/installation-issue-with-matplotlib-python

Create a file ~/.matplotlib/matplotlibrc there and add the following code: backend: TkAgg

Go to hello_world folder and try:

Open a chart locally:

    python hello.py

Publish a chart to server:

    python hello.server

Publish a matplotlib chart to server:

    python plt_server.py
