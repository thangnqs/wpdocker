# Docker for WordPress and more

- Support https on local dev
- Support custom domain like https://dev.test, ...

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
- Put your content into `wordpress` folder
- Open on browser https://dev.test 

### MySQL
- Hostname: `localhost` | `3060`
- Usename: `wp` | password: `secret`
- Mysql hostname: `mysql`
- Database name: wp
- Use client MySQL to connect like TablePlus, MySQL Workbench ...


