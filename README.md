# Описание задания

1. Ставим Wordpress и на основе этой вёрстки создаём новую тему для него.
2. Обязательно необходимо дать админу возможность редактировать всё, что отмечено зелёным цветом на скриншоте http://view.xscreenshot.com/522b3ec2c910d1b5495e3396fcebb2c3 , в случае ссылок на аккаунты в соцсетях достаточно дать возможность отредактировать только ссылку.
3. Последние новости (отмечены синим цветом) не являются последними постами блога. Они отображаются только в сайдбаре, также необходимо, чтобы ссылки с них вели не на внутренние страницы, а на сторонние ресурсы (было бы неплохо использовать кастомные типы записей).
4. Готовый результат должен быть в виде архива с Wordpress (или ссылка на репозиторий на Github), **также необходим файл с дампом БД**.

## How to install and run HTML Framework
Our HTML Framework based on H5BP+Grunt+SASS.

Instalation procedure is similar for Win/Mac/Linux.

### 1. Install [Ruby](http://rubyinstaller.org/downloads/)
Ruby __2.3.X__ x64 installer (needed for SASS (grunt-contrib-sass).
 - Select __„Add Ruby executables to your PATH“__.

### 2. Install SASS+Compass
```
gem install sass
gem install compass
```
If you get SSL error — foolow [this steps](https://gist.github.com/luislavena/f064211759ee0f806c88#manual-solution-to-ssl-issue).

### 3. Install [Node.js](https://nodejs.org/en/download/current/)
Current (latest features), Windows Installer 64-bit (needed for Grunt).

### 4. Install Grunt
Run cmd as administrator and execute:
```
npm install grunt-cli -g
```

### 5. Install
Once run `dev\install.cmd` or execute in shell:
```shell
npm install --save-dev
```

### 6. Run
Start Grunt with `dev\start.cmd` or execute in shell:
```shell
grunt
grunt watch
```
