Statically compile PHP
======================

- `$ sudo apt-get install -y libxml2-dev` - http://drewsymo.com/2013/11/php-configure-error-xml2-config-not-found-please-check-your-libxml2-installation/
- `$ sudo apt-get install -y libcurl4-openssl-dev pkg-config` - http://serverfault.com/questions/415458/php-error-cannot-find-openssls-evp-h
- `$ sudo apt-get install -y libpng12-dev` - (configure: error: png.h not found) http://zgadzaj.com/how-to-install-php-53-and-52-together-on-ubuntu-1204
- `$ sudo apt-get install -y libfreetype6-dev` - (configure: error: freetype-config not found.) - http://www.omniweb.com/wordpress/?p=1040
- `$ ./configure --prefix=/tmp/php-5.6.5/compiled --disable-all --without-pear --enable-shared=no --enable-static=yes --enable-phar --enable-json --with-openssl --with-curl --with-mhash --with-gd --with-freetype-dir --enable-mbstring --enable-sockets`
- `$ make`
- `$ make install`

See http://php.net/manual/en/configure.about.php for more information on all configuration options.
