# Hacking Tips and Tools 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

<h1>Syllabus Hacker:</h1>

<h4>
Overview:
<br/>
<br/>
- Virtual machines and containers
<br/>
- Shell and scripting
<br/>
- Command-line environment
<br/>
- Data wrangling
<br/>
- Editors
<br/>
- Version control
<br/>
- Dotfiles and backups
<br/>
- Automation and machine introspection
<br/>  
- Program introspection and package/dependency management
 <br/>
- OS customization and Remote Machines
<br/>
- Web and browsers
<br/>
- Security and privacy
</h4>

# About the project

https://wmazoni-sds1.netlify.app

Hacking Tips and Tools is a repository to show as many summarized experiences as possible about hacking the full stack web and mobile application built and organized by [Jony Peixoto](https://jonypeixoto.com "Site de Jony Peixoto").

The application consists of a search by Google and externally to other networks such as the Deep Web and associates about the hacking world, where data is collected in operating systems: Windows, Linux, mainly in applications of internal tools of the Linux system.

## Mobile Linux Layout 
![Mobile 1](https://github.com/jonypeixoto/jonypeixoto/blob/main/assets/iphone-linux1.jpg) ![Mobile 2](https://github.com/jonypeixoto/jonypeixoto/blob/main/assets/iphone-linux2.jpg)

More information:

https://dualbootfun.github.io/dualboot/

<br/>

## Desktop Linux Layout 
![Desktop 1](https://github.com/jonypeixoto/jonypeixoto/blob/main/assets/desktop-linux1.jpg) ![Desktop 2](https://github.com/jonypeixoto/jonypeixoto/blob/main/assets/desktop-linux2.png)

More information:

https://www.linux.org

<br/>

## Desktop Prompt Command on Windows Layout
![Web 1](https://github.com/acenelio/assets/raw/main/sds1/web1.png)

![Web 2](https://github.com/acenelio/assets/raw/main/sds1/web2.png)

# Technologies used

## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Linux
Pré-requisitos: Must have a device that runs the Linux operating system.

<h1>Commands on the Linux Ubuntu:</h1>

<h2>Linux Navigation Commands:</h2>

  Bottom TAB help to auto-complete any name in yout prompt on the Ubuntu Linux

* ) ls - historical about the files on the Linux directory
* ) cd (name file) - open the file
* ) cd .. - comeback 1 file
* ) mkdir - create a file
* ) clear - clear the prompt command
* ) history - show all the historical commands used on the promt command
* ) reboot - restart the machine (PC, Notebook, etc)
* ) shutdown - turn off the machine (PC, Notebook, etc)
* ) rm -rf (name file)- delete the file (name file)
* ) CTRL + p - shows / types the last commands typed in the Prompt


<h2>Linux Commands:</h2>

* ) apt-get update  - updates only what is needed on Ubuntu Linux (security, etc)
* ) apt-get upgrade - update everything on Ubuntu Linux
* ) apt-get autoremove - remove what it is not necessary on Ubuntu Linux
* ) apt-get install (program name) - install the (program name)

Example: open the vim

FIRST) Insert command: vim teste
SECOND) Press the "i" key for write and "ESC" for exit to write
THIRD) Save the text document >> Press SHIFT + ":" + wq!

For check out the text document, for open the text document, use the command: vim teste

W - for save the text document
Q - exit of the text document
! - for force this command

EXTRAS: 

SHIFT + ":w" = Save the text without exit of the text document
SHIFT + ":q" = Exit of the text document

* ) S - accept a command
* ) n -  deny a command
* ) apt-get purge (name program) - uninstall the (program name)

RECOMMEND USE: "apt-get autoremove" to remove what's missing from the program

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Windows
Pré-requisitos: Must have a device that runs the Windows operating system.

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```

# Autor

Jonathan Pereira Peixoto

https://jonypeixoto.com/linkedin
