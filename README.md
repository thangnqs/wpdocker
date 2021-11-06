# WPDocker

A simple setup Web Development with Docker and WordPress

### Required
- Docker 
- WP-CLI ( https://wp-cli.org ) 
- WSL2 on Windows ( optional )

### Install
- Run `docker-compose up -d` on root project
- Go to `cd wordpress/` and `wp core download` to install WordPress lasted version. 
- Open `http://localhost:8080` see it working!

### MySQL
- hostname: localhost | 3060
- usename: wp | password: secret
- Use client MySQL to connect like TablePlus, MySQL Workbench ...

### Added 
- Works on WSL2 for Windows 10/11 ( https://docs.microsoft.com/en-us/windows/wsl/install )
- Added Support Apple Silicon M1 ( please remove `platform: linux/x86_64` when use Intel chip )

### Bugs
- `chmod -R 777 wordpress/` if `wordpress/` folder not working

#### If you see it works please press STAR for me! Thanks 
