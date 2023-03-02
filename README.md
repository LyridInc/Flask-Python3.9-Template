# Lyrid Python 3.9 Flask Template

## Set virtual environment(optional):
```
python -m venv venv
source lyrid-venv/bin/activate
```

## Run locally with:
```
pip install -r requirements.txt
python main.py
```

Open http://localhost:3000

## Edit the names (optional):
Open .lyrid-definition and change the App and Module name, because this will override another applications with the same name in the platform.

## Then submit to Lyrid Platform:

```
lc code submit
```
Wait until the cloud platform to finish with the build and the default deployment.

## Start hacking:

Edit the routes at /entry/entry.py with your custom API. 

Add more middlewares or your business logic in there.

<a href="https://app.lyrid.io/login?one-click-deploy=true&origin=github&repository-url=https://github.com/LyridInc/Flask-Python3.9-Template.git&env=empty&project-type=Flask&repo-name=Flask-Python3.9-Template">
  <button>
    <img src="/entry/dist/assets/svg/ocd_deploy_to_lyrid.svg" style="height: 50px; width:200px;"/>
  </button>
</a>

