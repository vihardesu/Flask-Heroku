# Production API Boilerplate
> Heroku - For production hosting
> Gunicorn - For scaling workers
> Flask - For serving codebase
> Python - codebase
___
#### Notes
* runtime.txt specifies Python Version
* requirements.txt must be up to date 
```
pip freeze > requirements.txt
```
* nltk.txt needed if using nltk downloads

#### To Deploy
```
git add .
git commit -m 'message'
git push heroku master
```