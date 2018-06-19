REACT-NATIVE:

+ General:

> react-native init <project_name> # criar estrutura de projeto

> react-native run-android # rodar build em emulador

//=============================================================================//

ANDROID STUDIO:

+ General:


+ Emuladores
+ Listar emuladores via Prompt:

> C:\Users\\%username%\AppData\Local\Android\sdk\tools\emulator -list-avds

+ Rodar emulador via Prompt:

> C:\Users\\%username%\AppData\Local\Android\sdk\emulator\emulator @Nexus_One


//=============================================================================//

NPM:

+ General:

> npm i -g npm # instalar/atualizar o gerenciador de pacotes NPM

> npm init # inicializar um projeto

> npm i nome_pacote --save <package>  # instalar pacote local adicionando na secao de dependencias do package.json

//=============================================================================//

GIT - HEROKU - GITHUB:

+ General:

https://devcenter.heroku.com/articles/git#tracking-your-app-in-git

https://devcenter.heroku.com/articles/git#creating-a-heroku-remote

https://devcenter.heroku.com/articles/git#deploying-code


+ Quick setup (push an existing repository from the command line)

> git remote add origin [https://github.com/user_name/repository_name.git]

> git push origin master


+ Subsequent deploys:

> git status

> git add .

> git commit -m "Subsequent deploy"

> git push heroku master # to heroku

> git push origin master # to github

> heroku logs

+ Clonning repository:

> heroku git:clone -a myapp

//=============================================================================//
