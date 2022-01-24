# md

Simple markdown pastebin powered by [Writing](https://github.com/josephernest/writing) with openresty backend and authorization

# Installation

1. `cp -r ./writing /var/www/writing`
2. `chown -R www-data /var/www/writing/_`
3. Setup your openresty installation to use `nginx.conf`. Do not forget to adjust server name.
4. Create admin account: `echo -ne "paSSword" > /var/www/writing/.admin/.password`

