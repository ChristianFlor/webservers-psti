# deploy-webservers-psti

## Recursos
- [Heroku](https://heroku.com) & [Heroku cli](https://devcenter.heroku.com/articles/heroku-cli)
- Demo: https://webservers-psti.herokuapp.com

## Comandos Usados

```bash
heroku login -i

heroku create webservers-psti --buildpack heroku/python

https://webservers-psti.herokuapp.com/ | https://git.heroku.com/webservers-psti.git

git init 

heroku git:remote -a webservers-psti

git remote add origin https://git.heroku.com/webservers-psti.git

// una ves configurado el repo pasamos a crear los archivos correspondientes

git add .

git commit -m "first deploy"

git push --set-upstream origin master
```
