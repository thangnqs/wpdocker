# Docker for WordPress and more

A simple setup Web Development with Docker :hearts: WordPress or any PHP application

Support on 
 - :white_check_mark: Mac Intel, Mac M1 Chip
 - :white_check_mark: Windows 10 / 11 with WSL2 
 - :white_check_mark: Linux
  

Follow the update and get an question to me on WordPress Group [https://www.facebook.com/groups/wordpressviet/posts/5154112297936613]


### Feature Updated 2022

- Add https on local dev
- Add custom domain like https://dev.test, ...

### Required
- Docker 
- WP-CLI ( https://wp-cli.org ) 
- WSL2 on Windows ( optional )
- Setup `mkcert` at https://github.com/FiloSottile/mkcert
- TablePlus, MySQL Workbench or any a client connect to MySQL


### Install

- `cd wpdocker` and `cd nginx` and `mkdir certs`
- Run `mkcert dev.test` and you have 2 files .pem
- Run `docker-compose up -d --build`
- Run `sudo chmod -R 777 wordpress/` ( optional )
- Open on browser https://dev.test 
- Warning: add `platform: linux/x86_64` when use MACOS M1 devices

### MySQL
- hostname: `localhost` | `3060`
- usename: `wp` | password: `secret`
- mysql hostname: `mysql`
- Use client MySQL to connect like TablePlus, MySQL Workbench ...

### Screenshots

<img src="screenshots/env.png" alt="drawing" />
<img src="screenshots/Screenshot_1.png" alt="drawing" />
<img src="screenshots/Screenshot_2.png" alt="drawing" />
<img src="screenshots/Screenshot_3.png" alt="drawing" />
<img src="screenshots/Screenshot_4.png" alt="drawing" />

### :+1: Work with me

Create a new Pull Request [https://github.com/thangnqs/wpdocker/pulls]

##### Buy me a Coffee :kissing_heart: :kissing_heart: :kissing_heart:

<img src="support-me-a-coffee.jpg" alt="drawing" width="200"/>

### And If you see it's works please press STAR :star: for me! Thanks 
