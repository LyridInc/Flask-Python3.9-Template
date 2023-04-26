# Lyrid Python 3.9 Flask Template

## SAMPLE TEMPLATE
![hi](/static/assets/img/lyrid_logo_large.png)
This template is for _language_ suitable for uploading to the Lyrid Platform.

## Prerequisites 
1. Register an account at [Lyrid Web Application](https://app.beta.lyrid.io/) 
2. Download our command line tool, [the lc](https://docs.lyrid.io/initialization)
3. Clone the repo 'git clone https://github.com/sample_here'

## Run locally with:
```
pip install -r requirements.txt
python manage.py runserver
```

## Set virtual environment(optional):
```
python -m venv lyrid-venv
source lyrid-venv/bin/activate
```

## Edit the names (optional):
Open .lyrid-definition and change the App and Module name, because this will override another applications with the same name in the platform.

## User can clone this repo, then Replace these variables in all files :
- YOUR_APP_NAME
- YOUR_MODULE_NAME
- YOUR_FUNCTION_NAME

To change your file information:
Open ```.lyrid-definition.YML``` file
Change ```name``` and ```module name``` to your choice and save.

### Start Coding!
Users can edit route url, settings, and views with custom APIs. 

### Submit to Lyrid 
Use our command line tool to easily upload your application to the cloud.
```
lc code submit
```

## Start hacking:
Edit the route url, settings, and views at /entry folder with your custom APIs. 

Add more middlewares or your business logic in there.

## Contact Us
Have any questions? We are here to help!
Email us at support@lyrid.io  

### Find us on social medias
- [Discord](https://discord.com/invite/xtCCtc9WAX)
- [LinkedIn](https://www.linkedin.com/company/lyrid/?viewAsMember=true)
- [Twitter](https://twitter.com/LyridInc)
- [Facebook](https://www.facebook.com/lyridinc)

<a href="https://app.lyrid.io/login?one-click-deploy=true&origin=github&repository-url=https://github.com/LyridInc/Flask-Python3.9-Template.git&env=empty&project-type=Flask&repo-name=Flask-Python3.9-Template">
  <button>
    <img src="/entry/dist/assets/svg/ocd_deploy_to_lyrid.svg" style="height: 50px; width:200px;"/>
  </button>
</a>

