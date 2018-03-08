NPM:

+ General:

npm init # inicializar um projeto

npm i nome_pacote --save <package>  # instalar pacote local adicionando na secao de dependencias do package.json

//=============================================================================//

HEROKU:

+ General:

https://devcenter.heroku.com/articles/git#tracking-your-app-in-git

https://devcenter.heroku.com/articles/git#creating-a-heroku-remote

https://devcenter.heroku.com/articles/git#deploying-code

+ Subsequent deploys:

git status

git add .

git commit -m "Subsequent deploy"

git push heroku master

heroku logs

+ Clonning repository:

heroku git:clone -a myapp

//=============================================================================//
