# full-stack-fe-eng

## What is full stack? What's a full stack engineer?

Let say everything from the client all the way up to the server, which is someone who can build an application from start to finish

Almost impossible to be good at every part of the stack. You can be good at the front-end, you can be good at probably some of the back-end. You might be good at databases. You might be good at security. You might be good at performance tuning.

## Why Full Stack

You can master all the techniques involved in a development project. You can make a prototype very rapidly. You can provide help to all the team members.

Full stack developers ensure the openness of application and they also work alongside graphic designers as well for features of web design and many other tasks. They are necessary to look into web projects from the start to its final form.

## Command Line

Every operating system have command line, whether its windows, mac or linux. Its consistent, the command line always gonna be the same.

- Fast
- Consistent
- Easier to automate

Command line are important because not all server have a GUI (Graphical User Interface) and theres no limitation, no matter how well designed the GUI you cannot encompass all the possibilities. Some example of more familiar command line :

- `cd` - change directory
- `ls` - list directory content
- `pwd` - print working directory
- `mkdir` - make directory
- `rmdir` - remove directory
- `cat` - show file contents
- `man` - command manual
- `less` - show file contents by page
- `rm` - remove file
- `echo` - repeat input

### Shells

Is the one that included with a lot of UNIX systems by default but it basically allows you to run command lines, and run a lot of the basic systems that come along with UNIX.

- shells - Command intepreter to interface with systems
- terminal - runs shells application

The shells is just a frontline that is the user interface of some sorts, and it just talk to the application or the OS which talk to the kernel, and the kernel is the core of operating system.

## Understanding the Internet

It works by using a packet routing network that follows Internet Protocol (IP) and Transport Control Protocol (TCP) [5]. TCP and IP work together to ensure that data transmission across the internet is consistent and reliable, no matter which device you're using or where you're using it. Basically a series of system globally interconnected devices. Not to be confused with intranet, which basically internet but private.

## Servers

It serves content and also respond request, it serves something back.

```sh
> node simpleServer.js 
Server started! listening on port 8080
```


## SSH

The Secure Shell Protocol is a cryptographic network protocol for operating network services securely over an unsecured network. Its most notable applications are remote login and command-line execution. SSH applications are based on a client–server architecture, connecting an SSH client instance with an SSH server.

```sh
> ls
id_rsa  id_rsa.pub known_hosts
> vim id_rsa
> vim id_rsa.pub
```

## Nginx

Nginx
Nginx, stylized as NGINX, nginx or NginX, is a web server that can also be used as a reverse proxy, load balancer, mail proxy and HTTP cache. The software was created by Igor Sysoev and publicly released in 2004. Nginx is free and open-source software, released under the terms of the 2-clause BSD license. it can do or act as :

- Reverse proxy
- Web server
- Proxy server

Some of nginx command line :
Install nginx

```
sudo apt install nginx
```

Start nginx

```
sudo service nginx start
```

Show nginx configuration

```
sudo less /etc/nginx/sites-available/default
```

Create and edit index.html

```
sudo vi /var/www/html/index.html
```

### Node.js

Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.

Install NodeJS and npm

```
sudo apt install nodejs npm
```

Install git

```
sudo apt install git
```

### Application Setup

Change ownership of the www directory to the current user

```
sudo chown -R $USER:$USER /var/www
```

Create application directory

```
mkdir /var/www/app
```

Move into app directory and initialize empty git repo

```
cd /var/www/app && git init
```

Create directories

```
mkdir -p ui/js ui/html ui/css
```

Create empty app file

```
touch app.js
```

Initialize project

```
npm init
```

install express

```
npm i express --save
```

edit app

```
vi app.js
```

Run application

```
node app.js
```
