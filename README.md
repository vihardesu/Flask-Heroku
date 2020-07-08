# Production API Boilerplate
> Heroku - For production hosting
> Gunicorn - For scaling workers
> Flask - For serving codebase
> Python - codebase
___
#### Notes
* runtime.txt specifies Python Version
* requirements.txt must be up to date 
* nltk.txt needed if using nltk downloads

#### To Deploy
```
pip freeze > requirements.txt
git add .
git commit -m 'message'
git push heroku master
```