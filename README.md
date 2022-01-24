# md

Simple markdown pastebin powered by [Writing](https://github.com/josephernest/writing) with openresty backend and authorization

# Installation

1. `cp -r ./writing /var/www/writing`
2. `chown -R www-data /var/www/writing/_`
3. Copy `nginx.conf` to `/etc/nginx/sites-enabled/md.conf` (or whatever path you are using). Do not forget to adjust server name.
4. Create admin account: `echo -ne "paSSword" > /var/www/writing/.admin/.password`

# Features

* Authorization
* Ridiculosly not secure
* Responsible LaTeX rendering (using MathJax)
* All backend code in a single openresty config file (using lua magic)

