<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `php`

-	[`php:7.0.7-cli`](#php707-cli)
-	[`php:7.0-cli`](#php70-cli)
-	[`php:7-cli`](#php7-cli)
-	[`php:cli`](#phpcli)
-	[`php:7.0.7`](#php707)
-	[`php:7.0`](#php70)
-	[`php:7`](#php7)
-	[`php:latest`](#phplatest)
-	[`php:7.0.7-alpine`](#php707-alpine)
-	[`php:7.0-alpine`](#php70-alpine)
-	[`php:7-alpine`](#php7-alpine)
-	[`php:alpine`](#phpalpine)
-	[`php:7.0.7-apache`](#php707-apache)
-	[`php:7.0-apache`](#php70-apache)
-	[`php:7-apache`](#php7-apache)
-	[`php:apache`](#phpapache)
-	[`php:7.0.7-fpm`](#php707-fpm)
-	[`php:7.0-fpm`](#php70-fpm)
-	[`php:7-fpm`](#php7-fpm)
-	[`php:fpm`](#phpfpm)
-	[`php:7.0.7-fpm-alpine`](#php707-fpm-alpine)
-	[`php:7.0-fpm-alpine`](#php70-fpm-alpine)
-	[`php:7-fpm-alpine`](#php7-fpm-alpine)
-	[`php:fpm-alpine`](#phpfpm-alpine)
-	[`php:7.0.7-zts`](#php707-zts)
-	[`php:7.0-zts`](#php70-zts)
-	[`php:7-zts`](#php7-zts)
-	[`php:zts`](#phpzts)
-	[`php:7.0.7-zts-alpine`](#php707-zts-alpine)
-	[`php:7.0-zts-alpine`](#php70-zts-alpine)
-	[`php:7-zts-alpine`](#php7-zts-alpine)
-	[`php:zts-alpine`](#phpzts-alpine)
-	[`php:5.6.22-cli`](#php5622-cli)
-	[`php:5.6-cli`](#php56-cli)
-	[`php:5-cli`](#php5-cli)
-	[`php:5.6.22`](#php5622)
-	[`php:5.6`](#php56)
-	[`php:5`](#php5)
-	[`php:5.6.22-alpine`](#php5622-alpine)
-	[`php:5.6-alpine`](#php56-alpine)
-	[`php:5-alpine`](#php5-alpine)
-	[`php:5.6.22-apache`](#php5622-apache)
-	[`php:5.6-apache`](#php56-apache)
-	[`php:5-apache`](#php5-apache)
-	[`php:5.6.22-fpm`](#php5622-fpm)
-	[`php:5.6-fpm`](#php56-fpm)
-	[`php:5-fpm`](#php5-fpm)
-	[`php:5.6.22-fpm-alpine`](#php5622-fpm-alpine)
-	[`php:5.6-fpm-alpine`](#php56-fpm-alpine)
-	[`php:5-fpm-alpine`](#php5-fpm-alpine)
-	[`php:5.6.22-zts`](#php5622-zts)
-	[`php:5.6-zts`](#php56-zts)
-	[`php:5-zts`](#php5-zts)
-	[`php:5.6.22-zts-alpine`](#php5622-zts-alpine)
-	[`php:5.6-zts-alpine`](#php56-zts-alpine)
-	[`php:5-zts-alpine`](#php5-zts-alpine)
-	[`php:5.5.36-cli`](#php5536-cli)
-	[`php:5.5-cli`](#php55-cli)
-	[`php:5.5.36`](#php5536)
-	[`php:5.5`](#php55)
-	[`php:5.5.36-alpine`](#php5536-alpine)
-	[`php:5.5-alpine`](#php55-alpine)
-	[`php:5.5.36-apache`](#php5536-apache)
-	[`php:5.5-apache`](#php55-apache)
-	[`php:5.5.36-fpm`](#php5536-fpm)
-	[`php:5.5-fpm`](#php55-fpm)
-	[`php:5.5.36-fpm-alpine`](#php5536-fpm-alpine)
-	[`php:5.5-fpm-alpine`](#php55-fpm-alpine)
-	[`php:5.5.36-zts`](#php5536-zts)
-	[`php:5.5-zts`](#php55-zts)
-	[`php:5.5.36-zts-alpine`](#php5536-zts-alpine)
-	[`php:5.5-zts-alpine`](#php55-zts-alpine)

## `php:7.0.7-cli`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7.0-cli`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:7.0-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7-cli`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:7-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:cli`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7.0.7`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7.0`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:7.0` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:7` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:latest`

```console
$ docker pull php@sha256:fc36390c8ae785b05ef28434049efaea9f2df2693a503942eeeb09356250ae67
```

-	Platforms:
	-	linux; amd64

### `php:latest` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.1 MB (166101137 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c08e8e438e7b653aacd91a923ab3a1f69d04e9dd55d511b1765e0eb3da43466b`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:35:59 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:35:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:36:00 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:42:40 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 20:59:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 20:59:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:64a34b83f443e4c6e0a038580e557dd39975e41f6d1d56c3f57c70cb9b3d72fd`  
		Last Modified: Wed, 15 Jun 2016 21:01:31 GMT  
		Size: 37.4 MB (37403263 bytes)
	-	`sha256:3a829750701724b84028ecb36e5a44d4c11e7c2ca9f757e1ae177195ba9f92bf`  
		Last Modified: Wed, 15 Jun 2016 21:01:09 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7.0.7-alpine`

```console
$ docker pull php@sha256:60b5675883f0b1243b1f96d2e3ce5d37be4334cf4834993302bad885648526ad
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42893141 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:cd953e3cc8bc51b5d016ade0304311b18a59ea4d00acac5eea5f7f63bfacd27a`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 18:15:09 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:20:44 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:00 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:00 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:dd1c08dc0b3544afaf20beb3f29694c86bf116a4e7122202c67235f15ad9bb1b`  
		Last Modified: Wed, 08 Jun 2016 22:06:07 GMT  
		Size: 39.9 MB (39856867 bytes)
	-	`sha256:eeeae5f6643f6ce433d0b4e4eaad563d50389e512ca77a1d88708388f9af6c0a`  
		Last Modified: Wed, 15 Jun 2016 21:02:13 GMT  
		Size: 1.7 KB (1743 bytes)

## `php:7.0-alpine`

```console
$ docker pull php@sha256:60b5675883f0b1243b1f96d2e3ce5d37be4334cf4834993302bad885648526ad
```

-	Platforms:
	-	linux; amd64

### `php:7.0-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42893141 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:cd953e3cc8bc51b5d016ade0304311b18a59ea4d00acac5eea5f7f63bfacd27a`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 18:15:09 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:20:44 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:00 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:00 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:dd1c08dc0b3544afaf20beb3f29694c86bf116a4e7122202c67235f15ad9bb1b`  
		Last Modified: Wed, 08 Jun 2016 22:06:07 GMT  
		Size: 39.9 MB (39856867 bytes)
	-	`sha256:eeeae5f6643f6ce433d0b4e4eaad563d50389e512ca77a1d88708388f9af6c0a`  
		Last Modified: Wed, 15 Jun 2016 21:02:13 GMT  
		Size: 1.7 KB (1743 bytes)

## `php:7-alpine`

```console
$ docker pull php@sha256:60b5675883f0b1243b1f96d2e3ce5d37be4334cf4834993302bad885648526ad
```

-	Platforms:
	-	linux; amd64

### `php:7-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42893141 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:cd953e3cc8bc51b5d016ade0304311b18a59ea4d00acac5eea5f7f63bfacd27a`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 18:15:09 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:20:44 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:00 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:00 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:dd1c08dc0b3544afaf20beb3f29694c86bf116a4e7122202c67235f15ad9bb1b`  
		Last Modified: Wed, 08 Jun 2016 22:06:07 GMT  
		Size: 39.9 MB (39856867 bytes)
	-	`sha256:eeeae5f6643f6ce433d0b4e4eaad563d50389e512ca77a1d88708388f9af6c0a`  
		Last Modified: Wed, 15 Jun 2016 21:02:13 GMT  
		Size: 1.7 KB (1743 bytes)

## `php:alpine`

```console
$ docker pull php@sha256:60b5675883f0b1243b1f96d2e3ce5d37be4334cf4834993302bad885648526ad
```

-	Platforms:
	-	linux; amd64

### `php:alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42893141 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:cd953e3cc8bc51b5d016ade0304311b18a59ea4d00acac5eea5f7f63bfacd27a`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 18:15:09 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:15:10 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:20:44 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:00 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:00 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:dd1c08dc0b3544afaf20beb3f29694c86bf116a4e7122202c67235f15ad9bb1b`  
		Last Modified: Wed, 08 Jun 2016 22:06:07 GMT  
		Size: 39.9 MB (39856867 bytes)
	-	`sha256:eeeae5f6643f6ce433d0b4e4eaad563d50389e512ca77a1d88708388f9af6c0a`  
		Last Modified: Wed, 15 Jun 2016 21:02:13 GMT  
		Size: 1.7 KB (1743 bytes)

## `php:7.0.7-apache`

```console
$ docker pull php@sha256:f3543d35f1451126385d05a3b3bdb1f58f94d7d2d2a6e1febb798ccaebd4ff11
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **179.4 MB (179383170 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:8f437e6425c59c6b958b2d9b54c8b2b8acd7a77500a6a5318e22bf3afd153b22`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 02:43:46 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:49:02 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:02 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:02 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:03 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:03 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:04 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:f126ded007047371919cad80ee6c4d931e00549e94c540cef0919236c89d51bf`  
		Last Modified: Tue, 14 Jun 2016 21:46:00 GMT  
		Size: 47.8 MB (47805918 bytes)
	-	`sha256:3223fd1fe116015480fa56fc7250f693aaf4a1493920ac76e9f9088b99d7916a`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 1.8 KB (1751 bytes)
	-	`sha256:ee35ae4a615fbbb1c0584b41f8b234ebedcd3a7ef7efc4d07e903843f6e22af2`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 290.0 B

## `php:7.0-apache`

```console
$ docker pull php@sha256:f3543d35f1451126385d05a3b3bdb1f58f94d7d2d2a6e1febb798ccaebd4ff11
```

-	Platforms:
	-	linux; amd64

### `php:7.0-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **179.4 MB (179383170 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:8f437e6425c59c6b958b2d9b54c8b2b8acd7a77500a6a5318e22bf3afd153b22`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 02:43:46 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:49:02 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:02 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:02 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:03 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:03 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:04 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:f126ded007047371919cad80ee6c4d931e00549e94c540cef0919236c89d51bf`  
		Last Modified: Tue, 14 Jun 2016 21:46:00 GMT  
		Size: 47.8 MB (47805918 bytes)
	-	`sha256:3223fd1fe116015480fa56fc7250f693aaf4a1493920ac76e9f9088b99d7916a`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 1.8 KB (1751 bytes)
	-	`sha256:ee35ae4a615fbbb1c0584b41f8b234ebedcd3a7ef7efc4d07e903843f6e22af2`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 290.0 B

## `php:7-apache`

```console
$ docker pull php@sha256:f3543d35f1451126385d05a3b3bdb1f58f94d7d2d2a6e1febb798ccaebd4ff11
```

-	Platforms:
	-	linux; amd64

### `php:7-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **179.4 MB (179383170 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:8f437e6425c59c6b958b2d9b54c8b2b8acd7a77500a6a5318e22bf3afd153b22`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 02:43:46 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:49:02 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:02 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:02 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:03 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:03 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:04 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:f126ded007047371919cad80ee6c4d931e00549e94c540cef0919236c89d51bf`  
		Last Modified: Tue, 14 Jun 2016 21:46:00 GMT  
		Size: 47.8 MB (47805918 bytes)
	-	`sha256:3223fd1fe116015480fa56fc7250f693aaf4a1493920ac76e9f9088b99d7916a`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 1.8 KB (1751 bytes)
	-	`sha256:ee35ae4a615fbbb1c0584b41f8b234ebedcd3a7ef7efc4d07e903843f6e22af2`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 290.0 B

## `php:apache`

```console
$ docker pull php@sha256:f3543d35f1451126385d05a3b3bdb1f58f94d7d2d2a6e1febb798ccaebd4ff11
```

-	Platforms:
	-	linux; amd64

### `php:apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **179.4 MB (179383170 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:8f437e6425c59c6b958b2d9b54c8b2b8acd7a77500a6a5318e22bf3afd153b22`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 02:43:46 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:43:47 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:49:02 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:02 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:02 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:03 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:03 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:04 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:f126ded007047371919cad80ee6c4d931e00549e94c540cef0919236c89d51bf`  
		Last Modified: Tue, 14 Jun 2016 21:46:00 GMT  
		Size: 47.8 MB (47805918 bytes)
	-	`sha256:3223fd1fe116015480fa56fc7250f693aaf4a1493920ac76e9f9088b99d7916a`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 1.8 KB (1751 bytes)
	-	`sha256:ee35ae4a615fbbb1c0584b41f8b234ebedcd3a7ef7efc4d07e903843f6e22af2`  
		Last Modified: Wed, 15 Jun 2016 21:02:36 GMT  
		Size: 290.0 B

## `php:7.0.7-fpm`

```console
$ docker pull php@sha256:196e6b30dba5efa72048d55b2fb208e5fded398053b0aa009ac1020b11674597
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **169.6 MB (169582581 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7f4e479d07f371420d7e37f35299685073f7f596af89a578d194efb184486a44`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 02:49:05 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:55:54 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:05 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:06 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:07 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:08 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:08 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:6120681ee5f7c089835f29f8b6541e7e4448ffae87936452260226edb1b31772`  
		Last Modified: Tue, 14 Jun 2016 21:47:46 GMT  
		Size: 40.9 MB (40876892 bytes)
	-	`sha256:80cc9c19278e5c156a89be91c81794debd9a020115945257c401d22dbdf1e8ae`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:d787b842ee97975f777267198ee7d24aaf09aedff9c42dc23e594c7a1031f062`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 127.0 B
	-	`sha256:142d4ea9ea2baa9c67e3afcc8d7b829008c72a7c4a302b3450fc7a3f22f31e77`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 7.7 KB (7689 bytes)

## `php:7.0-fpm`

```console
$ docker pull php@sha256:196e6b30dba5efa72048d55b2fb208e5fded398053b0aa009ac1020b11674597
```

-	Platforms:
	-	linux; amd64

### `php:7.0-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **169.6 MB (169582581 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7f4e479d07f371420d7e37f35299685073f7f596af89a578d194efb184486a44`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 02:49:05 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:55:54 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:05 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:06 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:07 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:08 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:08 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:6120681ee5f7c089835f29f8b6541e7e4448ffae87936452260226edb1b31772`  
		Last Modified: Tue, 14 Jun 2016 21:47:46 GMT  
		Size: 40.9 MB (40876892 bytes)
	-	`sha256:80cc9c19278e5c156a89be91c81794debd9a020115945257c401d22dbdf1e8ae`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:d787b842ee97975f777267198ee7d24aaf09aedff9c42dc23e594c7a1031f062`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 127.0 B
	-	`sha256:142d4ea9ea2baa9c67e3afcc8d7b829008c72a7c4a302b3450fc7a3f22f31e77`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 7.7 KB (7689 bytes)

## `php:7-fpm`

```console
$ docker pull php@sha256:196e6b30dba5efa72048d55b2fb208e5fded398053b0aa009ac1020b11674597
```

-	Platforms:
	-	linux; amd64

### `php:7-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **169.6 MB (169582581 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7f4e479d07f371420d7e37f35299685073f7f596af89a578d194efb184486a44`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 02:49:05 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:55:54 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:05 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:06 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:07 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:08 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:08 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:6120681ee5f7c089835f29f8b6541e7e4448ffae87936452260226edb1b31772`  
		Last Modified: Tue, 14 Jun 2016 21:47:46 GMT  
		Size: 40.9 MB (40876892 bytes)
	-	`sha256:80cc9c19278e5c156a89be91c81794debd9a020115945257c401d22dbdf1e8ae`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:d787b842ee97975f777267198ee7d24aaf09aedff9c42dc23e594c7a1031f062`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 127.0 B
	-	`sha256:142d4ea9ea2baa9c67e3afcc8d7b829008c72a7c4a302b3450fc7a3f22f31e77`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 7.7 KB (7689 bytes)

## `php:fpm`

```console
$ docker pull php@sha256:196e6b30dba5efa72048d55b2fb208e5fded398053b0aa009ac1020b11674597
```

-	Platforms:
	-	linux; amd64

### `php:fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **169.6 MB (169582581 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7f4e479d07f371420d7e37f35299685073f7f596af89a578d194efb184486a44`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 02:49:05 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:49:05 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 02:55:54 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:05 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:06 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:07 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:08 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:08 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:6120681ee5f7c089835f29f8b6541e7e4448ffae87936452260226edb1b31772`  
		Last Modified: Tue, 14 Jun 2016 21:47:46 GMT  
		Size: 40.9 MB (40876892 bytes)
	-	`sha256:80cc9c19278e5c156a89be91c81794debd9a020115945257c401d22dbdf1e8ae`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:d787b842ee97975f777267198ee7d24aaf09aedff9c42dc23e594c7a1031f062`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 127.0 B
	-	`sha256:142d4ea9ea2baa9c67e3afcc8d7b829008c72a7c4a302b3450fc7a3f22f31e77`  
		Last Modified: Wed, 15 Jun 2016 21:03:01 GMT  
		Size: 7.7 KB (7689 bytes)

## `php:7.0.7-fpm-alpine`

```console
$ docker pull php@sha256:adaa599c561cf66eb51f8a741bc2229237802fb49bd35bdaf0ee34f0e3ef8286
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **46.5 MB (46528049 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:86c28f7ac7f582435eafff96163c58d27f24b03fc992f98f2d5c1e3a2d32c332`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 18:32:56 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:38:42 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:10 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:10 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:12 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:12 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:13 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:4bbb183642cccd8c96745470fd747676ba842ffdbfcb266ea7f0ad27df209dc8`  
		Last Modified: Wed, 08 Jun 2016 22:08:45 GMT  
		Size: 43.5 MB (43483972 bytes)
	-	`sha256:6f90675cc30c3402e756148ce8b1f24ba478c94443cb895fc76d10efd74d3cc3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 1.7 KB (1746 bytes)
	-	`sha256:c85eb85ea26aef5624d031f2b7f542e0a3f66bf5045c9e163863a272ae8f9adb`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 127.0 B
	-	`sha256:db74e6319bfc5c0b6917053605d735706945486d6e9f66ca29fac0e3d1d8cbe3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 7.7 KB (7673 bytes)

## `php:7.0-fpm-alpine`

```console
$ docker pull php@sha256:adaa599c561cf66eb51f8a741bc2229237802fb49bd35bdaf0ee34f0e3ef8286
```

-	Platforms:
	-	linux; amd64

### `php:7.0-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **46.5 MB (46528049 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:86c28f7ac7f582435eafff96163c58d27f24b03fc992f98f2d5c1e3a2d32c332`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 18:32:56 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:38:42 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:10 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:10 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:12 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:12 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:13 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:4bbb183642cccd8c96745470fd747676ba842ffdbfcb266ea7f0ad27df209dc8`  
		Last Modified: Wed, 08 Jun 2016 22:08:45 GMT  
		Size: 43.5 MB (43483972 bytes)
	-	`sha256:6f90675cc30c3402e756148ce8b1f24ba478c94443cb895fc76d10efd74d3cc3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 1.7 KB (1746 bytes)
	-	`sha256:c85eb85ea26aef5624d031f2b7f542e0a3f66bf5045c9e163863a272ae8f9adb`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 127.0 B
	-	`sha256:db74e6319bfc5c0b6917053605d735706945486d6e9f66ca29fac0e3d1d8cbe3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 7.7 KB (7673 bytes)

## `php:7-fpm-alpine`

```console
$ docker pull php@sha256:adaa599c561cf66eb51f8a741bc2229237802fb49bd35bdaf0ee34f0e3ef8286
```

-	Platforms:
	-	linux; amd64

### `php:7-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **46.5 MB (46528049 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:86c28f7ac7f582435eafff96163c58d27f24b03fc992f98f2d5c1e3a2d32c332`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 18:32:56 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:38:42 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:10 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:10 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:12 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:12 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:13 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:4bbb183642cccd8c96745470fd747676ba842ffdbfcb266ea7f0ad27df209dc8`  
		Last Modified: Wed, 08 Jun 2016 22:08:45 GMT  
		Size: 43.5 MB (43483972 bytes)
	-	`sha256:6f90675cc30c3402e756148ce8b1f24ba478c94443cb895fc76d10efd74d3cc3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 1.7 KB (1746 bytes)
	-	`sha256:c85eb85ea26aef5624d031f2b7f542e0a3f66bf5045c9e163863a272ae8f9adb`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 127.0 B
	-	`sha256:db74e6319bfc5c0b6917053605d735706945486d6e9f66ca29fac0e3d1d8cbe3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 7.7 KB (7673 bytes)

## `php:fpm-alpine`

```console
$ docker pull php@sha256:adaa599c561cf66eb51f8a741bc2229237802fb49bd35bdaf0ee34f0e3ef8286
```

-	Platforms:
	-	linux; amd64

### `php:fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **46.5 MB (46528049 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:86c28f7ac7f582435eafff96163c58d27f24b03fc992f98f2d5c1e3a2d32c332`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 18:32:56 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:32:56 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:38:42 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:10 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:10 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:12 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:12 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:13 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:4bbb183642cccd8c96745470fd747676ba842ffdbfcb266ea7f0ad27df209dc8`  
		Last Modified: Wed, 08 Jun 2016 22:08:45 GMT  
		Size: 43.5 MB (43483972 bytes)
	-	`sha256:6f90675cc30c3402e756148ce8b1f24ba478c94443cb895fc76d10efd74d3cc3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 1.7 KB (1746 bytes)
	-	`sha256:c85eb85ea26aef5624d031f2b7f542e0a3f66bf5045c9e163863a272ae8f9adb`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 127.0 B
	-	`sha256:db74e6319bfc5c0b6917053605d735706945486d6e9f66ca29fac0e3d1d8cbe3`  
		Last Modified: Wed, 15 Jun 2016 21:03:23 GMT  
		Size: 7.7 KB (7673 bytes)

## `php:7.0.7-zts`

```console
$ docker pull php@sha256:b88f6a429f6db0145787f3e90b83891b3bdaa9c6c0d1fd6b8ae2570db6881f8a
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.2 MB (166157642 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:4ccd7c06db47eac926be91456425996922e83a0ce217b37edd027197ea58b88a`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 02:55:58 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 03:02:51 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:14 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:15 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:02b0e87d332f4976dc387225df7227af52d37783f02e5fbc4a8e096849dd4f1a`  
		Last Modified: Wed, 15 Jun 2016 21:04:09 GMT  
		Size: 37.5 MB (37459768 bytes)
	-	`sha256:eced5519a07282aac70ab8548a092746e6241b0616c61cc88ad4dc97f164d656`  
		Last Modified: Wed, 15 Jun 2016 21:03:47 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7.0-zts`

```console
$ docker pull php@sha256:b88f6a429f6db0145787f3e90b83891b3bdaa9c6c0d1fd6b8ae2570db6881f8a
```

-	Platforms:
	-	linux; amd64

### `php:7.0-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.2 MB (166157642 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:4ccd7c06db47eac926be91456425996922e83a0ce217b37edd027197ea58b88a`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 02:55:58 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 03:02:51 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:14 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:15 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:02b0e87d332f4976dc387225df7227af52d37783f02e5fbc4a8e096849dd4f1a`  
		Last Modified: Wed, 15 Jun 2016 21:04:09 GMT  
		Size: 37.5 MB (37459768 bytes)
	-	`sha256:eced5519a07282aac70ab8548a092746e6241b0616c61cc88ad4dc97f164d656`  
		Last Modified: Wed, 15 Jun 2016 21:03:47 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7-zts`

```console
$ docker pull php@sha256:b88f6a429f6db0145787f3e90b83891b3bdaa9c6c0d1fd6b8ae2570db6881f8a
```

-	Platforms:
	-	linux; amd64

### `php:7-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.2 MB (166157642 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:4ccd7c06db47eac926be91456425996922e83a0ce217b37edd027197ea58b88a`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 02:55:58 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 03:02:51 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:14 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:15 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:02b0e87d332f4976dc387225df7227af52d37783f02e5fbc4a8e096849dd4f1a`  
		Last Modified: Wed, 15 Jun 2016 21:04:09 GMT  
		Size: 37.5 MB (37459768 bytes)
	-	`sha256:eced5519a07282aac70ab8548a092746e6241b0616c61cc88ad4dc97f164d656`  
		Last Modified: Wed, 15 Jun 2016 21:03:47 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:zts`

```console
$ docker pull php@sha256:b88f6a429f6db0145787f3e90b83891b3bdaa9c6c0d1fd6b8ae2570db6881f8a
```

-	Platforms:
	-	linux; amd64

### `php:zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **166.2 MB (166157642 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:4ccd7c06db47eac926be91456425996922e83a0ce217b37edd027197ea58b88a`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 02:55:58 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_VERSION=7.0.7
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Fri, 10 Jun 2016 02:55:59 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Fri, 10 Jun 2016 03:02:51 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:14 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:15 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:02b0e87d332f4976dc387225df7227af52d37783f02e5fbc4a8e096849dd4f1a`  
		Last Modified: Wed, 15 Jun 2016 21:04:09 GMT  
		Size: 37.5 MB (37459768 bytes)
	-	`sha256:eced5519a07282aac70ab8548a092746e6241b0616c61cc88ad4dc97f164d656`  
		Last Modified: Wed, 15 Jun 2016 21:03:47 GMT  
		Size: 1.8 KB (1754 bytes)

## `php:7.0.7-zts-alpine`

```console
$ docker pull php@sha256:84e814b1e366e793cd1d2f710745de29fdd1efaa85a94cd0088c20b4e0c1c42f
```

-	Platforms:
	-	linux; amd64

### `php:7.0.7-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42919317 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:208e9a14326f8ed661e52194c10ec21835141f55ac10a8c8dd367a8d9c9cf431`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 18:45:40 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:51:32 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:17 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:17 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:cd7cb6aeb9b7cb7b277edc1b845c7777a099df2b515efdfe10fac18e0340b288`  
		Last Modified: Wed, 08 Jun 2016 22:10:11 GMT  
		Size: 39.9 MB (39883042 bytes)
	-	`sha256:2034ed70399e2d23e4c8dae7e039794bdfb41e3ed08eaf71e96db0e4b47389c2`  
		Last Modified: Wed, 15 Jun 2016 21:04:32 GMT  
		Size: 1.7 KB (1744 bytes)

## `php:7.0-zts-alpine`

```console
$ docker pull php@sha256:84e814b1e366e793cd1d2f710745de29fdd1efaa85a94cd0088c20b4e0c1c42f
```

-	Platforms:
	-	linux; amd64

### `php:7.0-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42919317 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:208e9a14326f8ed661e52194c10ec21835141f55ac10a8c8dd367a8d9c9cf431`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 18:45:40 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:51:32 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:17 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:17 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:cd7cb6aeb9b7cb7b277edc1b845c7777a099df2b515efdfe10fac18e0340b288`  
		Last Modified: Wed, 08 Jun 2016 22:10:11 GMT  
		Size: 39.9 MB (39883042 bytes)
	-	`sha256:2034ed70399e2d23e4c8dae7e039794bdfb41e3ed08eaf71e96db0e4b47389c2`  
		Last Modified: Wed, 15 Jun 2016 21:04:32 GMT  
		Size: 1.7 KB (1744 bytes)

## `php:7-zts-alpine`

```console
$ docker pull php@sha256:84e814b1e366e793cd1d2f710745de29fdd1efaa85a94cd0088c20b4e0c1c42f
```

-	Platforms:
	-	linux; amd64

### `php:7-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42919317 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:208e9a14326f8ed661e52194c10ec21835141f55ac10a8c8dd367a8d9c9cf431`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 18:45:40 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:51:32 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:17 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:17 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:cd7cb6aeb9b7cb7b277edc1b845c7777a099df2b515efdfe10fac18e0340b288`  
		Last Modified: Wed, 08 Jun 2016 22:10:11 GMT  
		Size: 39.9 MB (39883042 bytes)
	-	`sha256:2034ed70399e2d23e4c8dae7e039794bdfb41e3ed08eaf71e96db0e4b47389c2`  
		Last Modified: Wed, 15 Jun 2016 21:04:32 GMT  
		Size: 1.7 KB (1744 bytes)

## `php:zts-alpine`

```console
$ docker pull php@sha256:84e814b1e366e793cd1d2f710745de29fdd1efaa85a94cd0088c20b4e0c1c42f
```

-	Platforms:
	-	linux; amd64

### `php:zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **42.9 MB (42919317 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:208e9a14326f8ed661e52194c10ec21835141f55ac10a8c8dd367a8d9c9cf431`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 18:45:40 GMT
ENV GPG_KEYS=1A4E8B7277C42E53DBA9C7B9BCAA30EA9C0D5763
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_VERSION=7.0.7
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_FILENAME=php-7.0.7.tar.xz
# Wed, 08 Jun 2016 18:45:40 GMT
ENV PHP_SHA256=9cc64a7459242c79c10e79d74feaf5bae3541f604966ceb600c3d2e8f5fe4794
# Wed, 08 Jun 2016 18:51:32 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:17 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:17 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:cd7cb6aeb9b7cb7b277edc1b845c7777a099df2b515efdfe10fac18e0340b288`  
		Last Modified: Wed, 08 Jun 2016 22:10:11 GMT  
		Size: 39.9 MB (39883042 bytes)
	-	`sha256:2034ed70399e2d23e4c8dae7e039794bdfb41e3ed08eaf71e96db0e4b47389c2`  
		Last Modified: Wed, 15 Jun 2016 21:04:32 GMT  
		Size: 1.7 KB (1744 bytes)

## `php:5.6.22-cli`

```console
$ docker pull php@sha256:4990cdcc8066bae092f8c784153896cc235d3dc996a0e8aa8eb84457b570a77e
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.7 MB (151747526 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1f5fa19c7d40c29d86722dbb8d0cb52b22e372ffa1c291482da6d01523cb3220`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:02:53 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:09:15 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:19 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:19 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:37bad9559a54cc5001286076c79add50645227ab7b87784d7d6fa3b2087cba00`  
		Last Modified: Wed, 15 Jun 2016 21:05:14 GMT  
		Size: 23.0 MB (23049651 bytes)
	-	`sha256:c6f09d87ddfb00dc179677fd40ab47c9d6610b4c9cabc8fd201cb1725e0fcdbc`  
		Last Modified: Wed, 15 Jun 2016 21:04:55 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5.6-cli`

```console
$ docker pull php@sha256:4990cdcc8066bae092f8c784153896cc235d3dc996a0e8aa8eb84457b570a77e
```

-	Platforms:
	-	linux; amd64

### `php:5.6-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.7 MB (151747526 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1f5fa19c7d40c29d86722dbb8d0cb52b22e372ffa1c291482da6d01523cb3220`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:02:53 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:09:15 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:19 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:19 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:37bad9559a54cc5001286076c79add50645227ab7b87784d7d6fa3b2087cba00`  
		Last Modified: Wed, 15 Jun 2016 21:05:14 GMT  
		Size: 23.0 MB (23049651 bytes)
	-	`sha256:c6f09d87ddfb00dc179677fd40ab47c9d6610b4c9cabc8fd201cb1725e0fcdbc`  
		Last Modified: Wed, 15 Jun 2016 21:04:55 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5-cli`

```console
$ docker pull php@sha256:4990cdcc8066bae092f8c784153896cc235d3dc996a0e8aa8eb84457b570a77e
```

-	Platforms:
	-	linux; amd64

### `php:5-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.7 MB (151747526 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1f5fa19c7d40c29d86722dbb8d0cb52b22e372ffa1c291482da6d01523cb3220`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:02:53 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:09:15 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:19 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:19 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:37bad9559a54cc5001286076c79add50645227ab7b87784d7d6fa3b2087cba00`  
		Last Modified: Wed, 15 Jun 2016 21:05:14 GMT  
		Size: 23.0 MB (23049651 bytes)
	-	`sha256:c6f09d87ddfb00dc179677fd40ab47c9d6610b4c9cabc8fd201cb1725e0fcdbc`  
		Last Modified: Wed, 15 Jun 2016 21:04:55 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5.6.22`

```console
$ docker pull php@sha256:4990cdcc8066bae092f8c784153896cc235d3dc996a0e8aa8eb84457b570a77e
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.7 MB (151747526 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1f5fa19c7d40c29d86722dbb8d0cb52b22e372ffa1c291482da6d01523cb3220`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:02:53 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:09:15 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:19 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:19 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:37bad9559a54cc5001286076c79add50645227ab7b87784d7d6fa3b2087cba00`  
		Last Modified: Wed, 15 Jun 2016 21:05:14 GMT  
		Size: 23.0 MB (23049651 bytes)
	-	`sha256:c6f09d87ddfb00dc179677fd40ab47c9d6610b4c9cabc8fd201cb1725e0fcdbc`  
		Last Modified: Wed, 15 Jun 2016 21:04:55 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5.6`

```console
$ docker pull php@sha256:4990cdcc8066bae092f8c784153896cc235d3dc996a0e8aa8eb84457b570a77e
```

-	Platforms:
	-	linux; amd64

### `php:5.6` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.7 MB (151747526 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1f5fa19c7d40c29d86722dbb8d0cb52b22e372ffa1c291482da6d01523cb3220`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:02:53 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:09:15 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:19 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:19 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:37bad9559a54cc5001286076c79add50645227ab7b87784d7d6fa3b2087cba00`  
		Last Modified: Wed, 15 Jun 2016 21:05:14 GMT  
		Size: 23.0 MB (23049651 bytes)
	-	`sha256:c6f09d87ddfb00dc179677fd40ab47c9d6610b4c9cabc8fd201cb1725e0fcdbc`  
		Last Modified: Wed, 15 Jun 2016 21:04:55 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5`

```console
$ docker pull php@sha256:4990cdcc8066bae092f8c784153896cc235d3dc996a0e8aa8eb84457b570a77e
```

-	Platforms:
	-	linux; amd64

### `php:5` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.7 MB (151747526 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1f5fa19c7d40c29d86722dbb8d0cb52b22e372ffa1c291482da6d01523cb3220`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:02:53 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:02:53 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:09:15 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:19 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:19 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:37bad9559a54cc5001286076c79add50645227ab7b87784d7d6fa3b2087cba00`  
		Last Modified: Wed, 15 Jun 2016 21:05:14 GMT  
		Size: 23.0 MB (23049651 bytes)
	-	`sha256:c6f09d87ddfb00dc179677fd40ab47c9d6610b4c9cabc8fd201cb1725e0fcdbc`  
		Last Modified: Wed, 15 Jun 2016 21:04:55 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5.6.22-alpine`

```console
$ docker pull php@sha256:31f94510a479a910878671c3995a8e11ff20bb12a834321eb4d26313c33c0f85
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.8 MB (27788192 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b51c1841dd434455e11baed7c988c88dccc214e07cd7fcdfb9e4c98de463a2e0`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:33:28 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 17:38:53 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:21 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:21 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:8ac28c8115df742165a2e0e3938f9ed1ae79b1a87b47b4d8bf9776638a1c7a6f`  
		Last Modified: Wed, 08 Jun 2016 22:00:51 GMT  
		Size: 24.8 MB (24751916 bytes)
	-	`sha256:51dd493f62267bd8709d9c85f76b509a917299d705f95a595a227c1599ae2f94`  
		Last Modified: Wed, 15 Jun 2016 21:05:44 GMT  
		Size: 1.7 KB (1745 bytes)

## `php:5.6-alpine`

```console
$ docker pull php@sha256:31f94510a479a910878671c3995a8e11ff20bb12a834321eb4d26313c33c0f85
```

-	Platforms:
	-	linux; amd64

### `php:5.6-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.8 MB (27788192 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b51c1841dd434455e11baed7c988c88dccc214e07cd7fcdfb9e4c98de463a2e0`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:33:28 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 17:38:53 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:21 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:21 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:8ac28c8115df742165a2e0e3938f9ed1ae79b1a87b47b4d8bf9776638a1c7a6f`  
		Last Modified: Wed, 08 Jun 2016 22:00:51 GMT  
		Size: 24.8 MB (24751916 bytes)
	-	`sha256:51dd493f62267bd8709d9c85f76b509a917299d705f95a595a227c1599ae2f94`  
		Last Modified: Wed, 15 Jun 2016 21:05:44 GMT  
		Size: 1.7 KB (1745 bytes)

## `php:5-alpine`

```console
$ docker pull php@sha256:31f94510a479a910878671c3995a8e11ff20bb12a834321eb4d26313c33c0f85
```

-	Platforms:
	-	linux; amd64

### `php:5-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.8 MB (27788192 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b51c1841dd434455e11baed7c988c88dccc214e07cd7fcdfb9e4c98de463a2e0`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:33:28 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 17:33:29 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 17:38:53 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:21 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:21 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:8ac28c8115df742165a2e0e3938f9ed1ae79b1a87b47b4d8bf9776638a1c7a6f`  
		Last Modified: Wed, 08 Jun 2016 22:00:51 GMT  
		Size: 24.8 MB (24751916 bytes)
	-	`sha256:51dd493f62267bd8709d9c85f76b509a917299d705f95a595a227c1599ae2f94`  
		Last Modified: Wed, 15 Jun 2016 21:05:44 GMT  
		Size: 1.7 KB (1745 bytes)

## `php:5.6.22-apache`

```console
$ docker pull php@sha256:c9d6aa36133e2d15c54f027c26f83c162b629b81847f3dcbd13e39f306d4386a
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **165.1 MB (165066665 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:306370e37ec1eb25d77de04c89a7c5b3114fdfe7f173796ac3c7ddcaa17f1425`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 03:09:18 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:14:28 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:23 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:23 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:24 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:24 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:25 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:e6088e923666bd67f46ac865a532fd4afad16a1f7d643bd656a266cb312c89e4`  
		Last Modified: Tue, 14 Jun 2016 21:44:33 GMT  
		Size: 33.5 MB (33489412 bytes)
	-	`sha256:bd4d72f8ce87197becf02103cc14257ae7b6760fd3b32a3ac0c0734ac0f97c68`  
		Last Modified: Wed, 15 Jun 2016 21:06:02 GMT  
		Size: 1.8 KB (1754 bytes)
	-	`sha256:59d686092751f65e3cd7cb85b1f97135fa4d309cf27c1b718d8a7139b709f7d8`  
		Last Modified: Wed, 15 Jun 2016 21:06:02 GMT  
		Size: 288.0 B

## `php:5.6-apache`

```console
$ docker pull php@sha256:c9d6aa36133e2d15c54f027c26f83c162b629b81847f3dcbd13e39f306d4386a
```

-	Platforms:
	-	linux; amd64

### `php:5.6-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **165.1 MB (165066665 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:306370e37ec1eb25d77de04c89a7c5b3114fdfe7f173796ac3c7ddcaa17f1425`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 03:09:18 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:14:28 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:23 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:23 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:24 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:24 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:25 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:e6088e923666bd67f46ac865a532fd4afad16a1f7d643bd656a266cb312c89e4`  
		Last Modified: Tue, 14 Jun 2016 21:44:33 GMT  
		Size: 33.5 MB (33489412 bytes)
	-	`sha256:bd4d72f8ce87197becf02103cc14257ae7b6760fd3b32a3ac0c0734ac0f97c68`  
		Last Modified: Wed, 15 Jun 2016 21:06:02 GMT  
		Size: 1.8 KB (1754 bytes)
	-	`sha256:59d686092751f65e3cd7cb85b1f97135fa4d309cf27c1b718d8a7139b709f7d8`  
		Last Modified: Wed, 15 Jun 2016 21:06:02 GMT  
		Size: 288.0 B

## `php:5-apache`

```console
$ docker pull php@sha256:c9d6aa36133e2d15c54f027c26f83c162b629b81847f3dcbd13e39f306d4386a
```

-	Platforms:
	-	linux; amd64

### `php:5-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **165.1 MB (165066665 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:306370e37ec1eb25d77de04c89a7c5b3114fdfe7f173796ac3c7ddcaa17f1425`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 03:09:18 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:09:18 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:14:28 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:23 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:23 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:24 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:24 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:25 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:e6088e923666bd67f46ac865a532fd4afad16a1f7d643bd656a266cb312c89e4`  
		Last Modified: Tue, 14 Jun 2016 21:44:33 GMT  
		Size: 33.5 MB (33489412 bytes)
	-	`sha256:bd4d72f8ce87197becf02103cc14257ae7b6760fd3b32a3ac0c0734ac0f97c68`  
		Last Modified: Wed, 15 Jun 2016 21:06:02 GMT  
		Size: 1.8 KB (1754 bytes)
	-	`sha256:59d686092751f65e3cd7cb85b1f97135fa4d309cf27c1b718d8a7139b709f7d8`  
		Last Modified: Wed, 15 Jun 2016 21:06:02 GMT  
		Size: 288.0 B

## `php:5.6.22-fpm`

```console
$ docker pull php@sha256:13af66c52122fb7daaa99930eabfa31cecde7525d065734426552ca5d2727a85
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **155.2 MB (155200727 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:025041cd3aa567ccb47f9db83aac68d398ed7821a105bbf55c8999dc22c1fcc6`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 03:14:30 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:21:00 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:26 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:27 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:28 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:29 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:29 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:be0f63860f5659d3f471dfae045f218e352752632f9d64ba06aae0bcca5e69f7`  
		Last Modified: Tue, 14 Jun 2016 21:46:51 GMT  
		Size: 26.5 MB (26495100 bytes)
	-	`sha256:40fc717066353458a82cd4e50ce8101c8e1a330ecc77383b52a685f9d4bb8acb`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:3274529208189965681c34caba255b2974c2e4388334fbd3a038849354b65555`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 126.0 B
	-	`sha256:a70691570f0e14786222ac8f7cc09e86bfc45597466d5229981e36962d68306a`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 7.6 KB (7628 bytes)

## `php:5.6-fpm`

```console
$ docker pull php@sha256:13af66c52122fb7daaa99930eabfa31cecde7525d065734426552ca5d2727a85
```

-	Platforms:
	-	linux; amd64

### `php:5.6-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **155.2 MB (155200727 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:025041cd3aa567ccb47f9db83aac68d398ed7821a105bbf55c8999dc22c1fcc6`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 03:14:30 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:21:00 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:26 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:27 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:28 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:29 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:29 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:be0f63860f5659d3f471dfae045f218e352752632f9d64ba06aae0bcca5e69f7`  
		Last Modified: Tue, 14 Jun 2016 21:46:51 GMT  
		Size: 26.5 MB (26495100 bytes)
	-	`sha256:40fc717066353458a82cd4e50ce8101c8e1a330ecc77383b52a685f9d4bb8acb`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:3274529208189965681c34caba255b2974c2e4388334fbd3a038849354b65555`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 126.0 B
	-	`sha256:a70691570f0e14786222ac8f7cc09e86bfc45597466d5229981e36962d68306a`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 7.6 KB (7628 bytes)

## `php:5-fpm`

```console
$ docker pull php@sha256:13af66c52122fb7daaa99930eabfa31cecde7525d065734426552ca5d2727a85
```

-	Platforms:
	-	linux; amd64

### `php:5-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **155.2 MB (155200727 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:025041cd3aa567ccb47f9db83aac68d398ed7821a105bbf55c8999dc22c1fcc6`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 03:14:30 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:14:31 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:21:00 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:26 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:27 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:28 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:29 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:29 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:be0f63860f5659d3f471dfae045f218e352752632f9d64ba06aae0bcca5e69f7`  
		Last Modified: Tue, 14 Jun 2016 21:46:51 GMT  
		Size: 26.5 MB (26495100 bytes)
	-	`sha256:40fc717066353458a82cd4e50ce8101c8e1a330ecc77383b52a685f9d4bb8acb`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:3274529208189965681c34caba255b2974c2e4388334fbd3a038849354b65555`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 126.0 B
	-	`sha256:a70691570f0e14786222ac8f7cc09e86bfc45597466d5229981e36962d68306a`  
		Last Modified: Wed, 15 Jun 2016 21:06:21 GMT  
		Size: 7.6 KB (7628 bytes)

## `php:5.6.22-fpm-alpine`

```console
$ docker pull php@sha256:9ac6c7aac357803eccda7a5f41897894e04f4f8e5eddb6b4cb34dc60c83954e2
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **31.4 MB (31418791 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:47c78efba8ca8b76b222a881bbd79a85cd957296dd7b6f87cea1f6c2799f2d88`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 17:50:36 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 17:50:36 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 17:50:37 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 17:50:37 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 17:56:08 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:31 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:31 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:33 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:33 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:34 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:58bc50067db416ca69ca011bfce0429b8f5a3cba9b67ac992794b6910d813d91`  
		Last Modified: Wed, 08 Jun 2016 22:03:01 GMT  
		Size: 28.4 MB (28374777 bytes)
	-	`sha256:524ad62623d88e2334ba89d68e03635260761a9dceb73783a5d415235d28b574`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 1.7 KB (1744 bytes)
	-	`sha256:9019042e15ef0018188471089ce90dcdf9ec6a6c409b997025118c66430a5dec`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 127.0 B
	-	`sha256:0d456aa9fbe7eacfb813ac9feb9a6d6a50d1a8f817956f94ae059535f7d87a7c`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 7.6 KB (7612 bytes)

## `php:5.6-fpm-alpine`

```console
$ docker pull php@sha256:9ac6c7aac357803eccda7a5f41897894e04f4f8e5eddb6b4cb34dc60c83954e2
```

-	Platforms:
	-	linux; amd64

### `php:5.6-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **31.4 MB (31418791 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:47c78efba8ca8b76b222a881bbd79a85cd957296dd7b6f87cea1f6c2799f2d88`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 17:50:36 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 17:50:36 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 17:50:37 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 17:50:37 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 17:56:08 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:31 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:31 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:33 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:33 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:34 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:58bc50067db416ca69ca011bfce0429b8f5a3cba9b67ac992794b6910d813d91`  
		Last Modified: Wed, 08 Jun 2016 22:03:01 GMT  
		Size: 28.4 MB (28374777 bytes)
	-	`sha256:524ad62623d88e2334ba89d68e03635260761a9dceb73783a5d415235d28b574`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 1.7 KB (1744 bytes)
	-	`sha256:9019042e15ef0018188471089ce90dcdf9ec6a6c409b997025118c66430a5dec`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 127.0 B
	-	`sha256:0d456aa9fbe7eacfb813ac9feb9a6d6a50d1a8f817956f94ae059535f7d87a7c`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 7.6 KB (7612 bytes)

## `php:5-fpm-alpine`

```console
$ docker pull php@sha256:9ac6c7aac357803eccda7a5f41897894e04f4f8e5eddb6b4cb34dc60c83954e2
```

-	Platforms:
	-	linux; amd64

### `php:5-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **31.4 MB (31418791 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:47c78efba8ca8b76b222a881bbd79a85cd957296dd7b6f87cea1f6c2799f2d88`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 17:50:36 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 17:50:36 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 17:50:37 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 17:50:37 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 17:56:08 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:31 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:31 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:33 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:33 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:34 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:58bc50067db416ca69ca011bfce0429b8f5a3cba9b67ac992794b6910d813d91`  
		Last Modified: Wed, 08 Jun 2016 22:03:01 GMT  
		Size: 28.4 MB (28374777 bytes)
	-	`sha256:524ad62623d88e2334ba89d68e03635260761a9dceb73783a5d415235d28b574`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 1.7 KB (1744 bytes)
	-	`sha256:9019042e15ef0018188471089ce90dcdf9ec6a6c409b997025118c66430a5dec`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 127.0 B
	-	`sha256:0d456aa9fbe7eacfb813ac9feb9a6d6a50d1a8f817956f94ae059535f7d87a7c`  
		Last Modified: Wed, 15 Jun 2016 21:06:40 GMT  
		Size: 7.6 KB (7612 bytes)

## `php:5.6.22-zts`

```console
$ docker pull php@sha256:a88b583dabd26bbdfb533cf10fb9b79bf1259ee636ad1ee72e24234364699398
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.8 MB (151798808 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:52c4f6ee5204e4c5df8ca68bc8fd652aab633a97a17d3bdc92b57c0ddb0b0e46`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 03:21:04 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:27:43 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:35 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:36 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:6cc83e11a6b9752e355ff4693eab48d8367581a61e7bd0a8159decaa800c393c`  
		Last Modified: Wed, 15 Jun 2016 21:07:17 GMT  
		Size: 23.1 MB (23100933 bytes)
	-	`sha256:64090d4f67f3d359e4627e2adae420864f1cb6a3ffa409dd2ce2d2a509f868c0`  
		Last Modified: Wed, 15 Jun 2016 21:07:00 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5.6-zts`

```console
$ docker pull php@sha256:a88b583dabd26bbdfb533cf10fb9b79bf1259ee636ad1ee72e24234364699398
```

-	Platforms:
	-	linux; amd64

### `php:5.6-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.8 MB (151798808 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:52c4f6ee5204e4c5df8ca68bc8fd652aab633a97a17d3bdc92b57c0ddb0b0e46`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 03:21:04 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:27:43 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:35 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:36 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:6cc83e11a6b9752e355ff4693eab48d8367581a61e7bd0a8159decaa800c393c`  
		Last Modified: Wed, 15 Jun 2016 21:07:17 GMT  
		Size: 23.1 MB (23100933 bytes)
	-	`sha256:64090d4f67f3d359e4627e2adae420864f1cb6a3ffa409dd2ce2d2a509f868c0`  
		Last Modified: Wed, 15 Jun 2016 21:07:00 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5-zts`

```console
$ docker pull php@sha256:a88b583dabd26bbdfb533cf10fb9b79bf1259ee636ad1ee72e24234364699398
```

-	Platforms:
	-	linux; amd64

### `php:5-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.8 MB (151798808 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:52c4f6ee5204e4c5df8ca68bc8fd652aab633a97a17d3bdc92b57c0ddb0b0e46`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 03:21:04 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_VERSION=5.6.22
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Fri, 10 Jun 2016 03:21:04 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Fri, 10 Jun 2016 03:27:43 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:35 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:36 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:6cc83e11a6b9752e355ff4693eab48d8367581a61e7bd0a8159decaa800c393c`  
		Last Modified: Wed, 15 Jun 2016 21:07:17 GMT  
		Size: 23.1 MB (23100933 bytes)
	-	`sha256:64090d4f67f3d359e4627e2adae420864f1cb6a3ffa409dd2ce2d2a509f868c0`  
		Last Modified: Wed, 15 Jun 2016 21:07:00 GMT  
		Size: 1.8 KB (1755 bytes)

## `php:5.6.22-zts-alpine`

```console
$ docker pull php@sha256:fd7109f2deecee50fd6673e24860e4e273ea0f73b9d5faad87a4bc33a37c04aa
```

-	Platforms:
	-	linux; amd64

### `php:5.6.22-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.8 MB (27838962 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a01610e1e642c91e6217f1c0688900c92612d30b503b332ee81502824c66b0a0`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 18:02:48 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 18:08:26 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:37 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:38 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:7f80e2be507d4691b57dcfb198070d014596c12715d15bc13f5cce8ecf4a6f37`  
		Last Modified: Wed, 08 Jun 2016 22:04:21 GMT  
		Size: 24.8 MB (24802689 bytes)
	-	`sha256:9b00559c9e689c74d3ab6b0828c833469b0dde3a00a251f7d80bf0cd1a09d43c`  
		Last Modified: Wed, 15 Jun 2016 21:07:37 GMT  
		Size: 1.7 KB (1742 bytes)

## `php:5.6-zts-alpine`

```console
$ docker pull php@sha256:fd7109f2deecee50fd6673e24860e4e273ea0f73b9d5faad87a4bc33a37c04aa
```

-	Platforms:
	-	linux; amd64

### `php:5.6-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.8 MB (27838962 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a01610e1e642c91e6217f1c0688900c92612d30b503b332ee81502824c66b0a0`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 18:02:48 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 18:08:26 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:37 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:38 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:7f80e2be507d4691b57dcfb198070d014596c12715d15bc13f5cce8ecf4a6f37`  
		Last Modified: Wed, 08 Jun 2016 22:04:21 GMT  
		Size: 24.8 MB (24802689 bytes)
	-	`sha256:9b00559c9e689c74d3ab6b0828c833469b0dde3a00a251f7d80bf0cd1a09d43c`  
		Last Modified: Wed, 15 Jun 2016 21:07:37 GMT  
		Size: 1.7 KB (1742 bytes)

## `php:5-zts-alpine`

```console
$ docker pull php@sha256:fd7109f2deecee50fd6673e24860e4e273ea0f73b9d5faad87a4bc33a37c04aa
```

-	Platforms:
	-	linux; amd64

### `php:5-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.8 MB (27838962 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a01610e1e642c91e6217f1c0688900c92612d30b503b332ee81502824c66b0a0`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 18:02:48 GMT
ENV GPG_KEYS=0BD78B5F97500D450838F95DFE857D9A90D90EC1 6E4F6AB321FDC07F2C332E3AC2BF0BC433CFC8B3
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_VERSION=5.6.22
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_FILENAME=php-5.6.22.tar.xz
# Wed, 08 Jun 2016 18:02:48 GMT
ENV PHP_SHA256=c96980d7de1d66c821a4ee5809df0076f925b2fe0b8c362d234d92f2f0a178e2
# Wed, 08 Jun 2016 18:08:26 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:37 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:38 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:7f80e2be507d4691b57dcfb198070d014596c12715d15bc13f5cce8ecf4a6f37`  
		Last Modified: Wed, 08 Jun 2016 22:04:21 GMT  
		Size: 24.8 MB (24802689 bytes)
	-	`sha256:9b00559c9e689c74d3ab6b0828c833469b0dde3a00a251f7d80bf0cd1a09d43c`  
		Last Modified: Wed, 15 Jun 2016 21:07:37 GMT  
		Size: 1.7 KB (1742 bytes)

## `php:5.5.36-cli`

```console
$ docker pull php@sha256:faece5de4d87152338a8892d070fa0b61cd25ba19f8ee29d7925732ddbfaf12c
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.0 MB (151038849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:15608c41fe7084d4e9ff4f12797e2f4e027b4a353e0cf18c8b569d61a9fc978d`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:27:45 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:27:46 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:34:08 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:39 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:40 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:3c4f3a9d2e592695d3d9359eda0fd09cc8d52499fe395b9ed7a36498d64ce321`  
		Last Modified: Wed, 15 Jun 2016 21:08:13 GMT  
		Size: 22.3 MB (22340976 bytes)
	-	`sha256:3ace97be5966c46cacac7744729d9d4a9b67767556173f63ba073ccd84904c17`  
		Last Modified: Wed, 15 Jun 2016 21:07:55 GMT  
		Size: 1.8 KB (1753 bytes)

## `php:5.5-cli`

```console
$ docker pull php@sha256:faece5de4d87152338a8892d070fa0b61cd25ba19f8ee29d7925732ddbfaf12c
```

-	Platforms:
	-	linux; amd64

### `php:5.5-cli` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.0 MB (151038849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:15608c41fe7084d4e9ff4f12797e2f4e027b4a353e0cf18c8b569d61a9fc978d`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:27:45 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:27:46 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:34:08 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:39 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:40 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:3c4f3a9d2e592695d3d9359eda0fd09cc8d52499fe395b9ed7a36498d64ce321`  
		Last Modified: Wed, 15 Jun 2016 21:08:13 GMT  
		Size: 22.3 MB (22340976 bytes)
	-	`sha256:3ace97be5966c46cacac7744729d9d4a9b67767556173f63ba073ccd84904c17`  
		Last Modified: Wed, 15 Jun 2016 21:07:55 GMT  
		Size: 1.8 KB (1753 bytes)

## `php:5.5.36`

```console
$ docker pull php@sha256:faece5de4d87152338a8892d070fa0b61cd25ba19f8ee29d7925732ddbfaf12c
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.0 MB (151038849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:15608c41fe7084d4e9ff4f12797e2f4e027b4a353e0cf18c8b569d61a9fc978d`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:27:45 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:27:46 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:34:08 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:39 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:40 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:3c4f3a9d2e592695d3d9359eda0fd09cc8d52499fe395b9ed7a36498d64ce321`  
		Last Modified: Wed, 15 Jun 2016 21:08:13 GMT  
		Size: 22.3 MB (22340976 bytes)
	-	`sha256:3ace97be5966c46cacac7744729d9d4a9b67767556173f63ba073ccd84904c17`  
		Last Modified: Wed, 15 Jun 2016 21:07:55 GMT  
		Size: 1.8 KB (1753 bytes)

## `php:5.5`

```console
$ docker pull php@sha256:faece5de4d87152338a8892d070fa0b61cd25ba19f8ee29d7925732ddbfaf12c
```

-	Platforms:
	-	linux; amd64

### `php:5.5` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.0 MB (151038849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:15608c41fe7084d4e9ff4f12797e2f4e027b4a353e0cf18c8b569d61a9fc978d`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 03:27:45 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:27:45 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:27:46 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:34:08 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:39 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:40 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:3c4f3a9d2e592695d3d9359eda0fd09cc8d52499fe395b9ed7a36498d64ce321`  
		Last Modified: Wed, 15 Jun 2016 21:08:13 GMT  
		Size: 22.3 MB (22340976 bytes)
	-	`sha256:3ace97be5966c46cacac7744729d9d4a9b67767556173f63ba073ccd84904c17`  
		Last Modified: Wed, 15 Jun 2016 21:07:55 GMT  
		Size: 1.8 KB (1753 bytes)

## `php:5.5.36-alpine`

```console
$ docker pull php@sha256:054b206f20b24074167554612111bd35308d29b2fd8e3a67fffa2cec622b79a2
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.1 MB (27081327 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a2d5a702ae07251ee3ff95164516dc94c17b3ceab6364192f5a93f6d85781d88`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 16:51:03 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Wed, 08 Jun 2016 16:51:03 GMT
ENV PHP_VERSION=5.5.36
# Wed, 08 Jun 2016 16:51:03 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Wed, 08 Jun 2016 16:51:03 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Wed, 08 Jun 2016 16:56:26 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:41 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:42 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:1deecf649ab473af51e61e9d92bcba19739bb301d1f7935de1d4613c4a7ec4a6`  
		Last Modified: Wed, 08 Jun 2016 21:56:51 GMT  
		Size: 24.0 MB (24045051 bytes)
	-	`sha256:9e47817f2e974872e2b178219342ed4a10a2c6bf09079db2373ef02b56a3de96`  
		Last Modified: Wed, 15 Jun 2016 21:08:36 GMT  
		Size: 1.7 KB (1745 bytes)

## `php:5.5-alpine`

```console
$ docker pull php@sha256:054b206f20b24074167554612111bd35308d29b2fd8e3a67fffa2cec622b79a2
```

-	Platforms:
	-	linux; amd64

### `php:5.5-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.1 MB (27081327 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a2d5a702ae07251ee3ff95164516dc94c17b3ceab6364192f5a93f6d85781d88`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 16:51:03 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Wed, 08 Jun 2016 16:51:03 GMT
ENV PHP_VERSION=5.5.36
# Wed, 08 Jun 2016 16:51:03 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Wed, 08 Jun 2016 16:51:03 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Wed, 08 Jun 2016 16:56:26 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:41 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:42 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:1deecf649ab473af51e61e9d92bcba19739bb301d1f7935de1d4613c4a7ec4a6`  
		Last Modified: Wed, 08 Jun 2016 21:56:51 GMT  
		Size: 24.0 MB (24045051 bytes)
	-	`sha256:9e47817f2e974872e2b178219342ed4a10a2c6bf09079db2373ef02b56a3de96`  
		Last Modified: Wed, 15 Jun 2016 21:08:36 GMT  
		Size: 1.7 KB (1745 bytes)

## `php:5.5.36-apache`

```console
$ docker pull php@sha256:2c9885c1172d9d78e115404776aed7a75489aa3fc043602afe876954c333b464
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **164.3 MB (164270434 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:d85c4753a377a31fb5f682a309787009782db4c9189d8a0fc7c4cecf4e5d7787`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 03:34:11 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:34:11 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:34:11 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:34:11 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:39:22 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:43 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:44 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:45 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:45 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:46 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:d8ba8662efa315a2933175419f314b9349abc8422d95e322800d29ba12310bc1`  
		Last Modified: Wed, 15 Jun 2016 21:09:10 GMT  
		Size: 32.7 MB (32693181 bytes)
	-	`sha256:4e433495218d2e7d65ee4a603eb0fc60954854f10ac26a61a5576306494e2ffd`  
		Last Modified: Wed, 15 Jun 2016 21:08:49 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:da368c12509f859e5405871151894c637cca3584a64a8390712da750f893422d`  
		Last Modified: Wed, 15 Jun 2016 21:08:50 GMT  
		Size: 289.0 B

## `php:5.5-apache`

```console
$ docker pull php@sha256:2c9885c1172d9d78e115404776aed7a75489aa3fc043602afe876954c333b464
```

-	Platforms:
	-	linux; amd64

### `php:5.5-apache` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **164.3 MB (164270434 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:d85c4753a377a31fb5f682a309787009782db4c9189d8a0fc7c4cecf4e5d7787`
-	Default Command: `["apache2-foreground"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:43:42 GMT
RUN apt-get update && apt-get install -y apache2-bin apache2.2-common --no-install-recommends && rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:43:43 GMT
RUN rm -rf /var/www/html && mkdir -p /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html && chown -R www-data:www-data /var/lock/apache2 /var/run/apache2 /var/log/apache2 /var/www/html
# Fri, 10 Jun 2016 02:43:44 GMT
RUN a2dismod mpm_event && a2enmod mpm_prefork
# Fri, 10 Jun 2016 02:43:45 GMT
RUN mv /etc/apache2/apache2.conf /etc/apache2/apache2.conf.dist && rm /etc/apache2/conf-enabled/* /etc/apache2/sites-enabled/*
# Fri, 10 Jun 2016 02:43:46 GMT
COPY file:83126aa7167396d9538d8cd3860fed68ccce351540fad4964ee1930c2ab74a9b in /etc/apache2/apache2.conf
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_BUILD_DEPS=apache2-dev
# Fri, 10 Jun 2016 02:43:46 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--with-apxs2
# Fri, 10 Jun 2016 03:34:11 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:34:11 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:34:11 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:34:11 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:39:22 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:43 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:44 GMT
COPY file:9af336f9cce358b296eebfb8895bbae6ac19492469a03e1b7c2f5c574807721d in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:45 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:45 GMT
EXPOSE 80/tcp
# Wed, 15 Jun 2016 21:00:46 GMT
CMD ["apache2-foreground"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:a3a94d3df9be4137d53c70f13e1bf0e40d300e41c9773a3b5b26d68d75f31797`  
		Last Modified: Tue, 14 Jun 2016 21:44:14 GMT  
		Size: 2.9 MB (2874106 bytes)
	-	`sha256:8d889f91ade23b56b99c85fc7dcf3196d91380bb21b461793cceea4c179055d0`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 324.0 B
	-	`sha256:6aa1b9bbdc5d5bcfae5f9b5659678b98f043b322968a432012ca470396bc5195`  
		Last Modified: Tue, 14 Jun 2016 21:44:11 GMT  
		Size: 434.0 B
	-	`sha256:777536a87cede6c7cfb17ee9cb2c94f935f08527cc2df874d95978ce88233166`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 3.4 KB (3365 bytes)
	-	`sha256:c9ba89109223f6a7c223588aec1ca33024360af02e68ab9e9e6430ef429f94a2`  
		Last Modified: Tue, 14 Jun 2016 21:44:10 GMT  
		Size: 862.0 B
	-	`sha256:d8ba8662efa315a2933175419f314b9349abc8422d95e322800d29ba12310bc1`  
		Last Modified: Wed, 15 Jun 2016 21:09:10 GMT  
		Size: 32.7 MB (32693181 bytes)
	-	`sha256:4e433495218d2e7d65ee4a603eb0fc60954854f10ac26a61a5576306494e2ffd`  
		Last Modified: Wed, 15 Jun 2016 21:08:49 GMT  
		Size: 1.8 KB (1753 bytes)
	-	`sha256:da368c12509f859e5405871151894c637cca3584a64a8390712da750f893422d`  
		Last Modified: Wed, 15 Jun 2016 21:08:50 GMT  
		Size: 289.0 B

## `php:5.5.36-fpm`

```console
$ docker pull php@sha256:2d1adf50035ae43e2fee187c60c697c35344835d48475a9bd79215a60d3e09c9
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **154.5 MB (154484103 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:8d66023c27ffadede3005ca0fa46650a52a1e41b803ae2a66819ae532d8a268e`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 03:39:24 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:39:24 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:39:25 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:39:25 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:45:56 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:47 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:48 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:49 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:50 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:50 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:8020dcdd1645824d56ce741773dce671e9dd6a11841b24d767bbb7b9630059f9`  
		Last Modified: Wed, 15 Jun 2016 21:09:46 GMT  
		Size: 25.8 MB (25778564 bytes)
	-	`sha256:75023e69945a2f15cf0816b2ab64f6bb59d60996c94d94ab7a2615414ccdeacc`  
		Last Modified: Wed, 15 Jun 2016 21:09:26 GMT  
		Size: 1.8 KB (1755 bytes)
	-	`sha256:560eed1016d692dc2ea55efd10bc4c50d96f234b003c375b110210a853bab6a1`  
		Last Modified: Wed, 15 Jun 2016 21:09:26 GMT  
		Size: 128.0 B
	-	`sha256:50d628eea821a18dc223c62bc57211d4e2a2dbba90bb475b56204603937f0a58`  
		Last Modified: Wed, 15 Jun 2016 21:09:26 GMT  
		Size: 7.5 KB (7536 bytes)

## `php:5.5-fpm`

```console
$ docker pull php@sha256:2d1adf50035ae43e2fee187c60c697c35344835d48475a9bd79215a60d3e09c9
```

-	Platforms:
	-	linux; amd64

### `php:5.5-fpm` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **154.5 MB (154484103 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:8d66023c27ffadede3005ca0fa46650a52a1e41b803ae2a66819ae532d8a268e`
-	Default Command: `["php-fpm"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:49:04 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Fri, 10 Jun 2016 03:39:24 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:39:24 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:39:25 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:39:25 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:45:56 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:47 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:48 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:49 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:50 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:50 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:8020dcdd1645824d56ce741773dce671e9dd6a11841b24d767bbb7b9630059f9`  
		Last Modified: Wed, 15 Jun 2016 21:09:46 GMT  
		Size: 25.8 MB (25778564 bytes)
	-	`sha256:75023e69945a2f15cf0816b2ab64f6bb59d60996c94d94ab7a2615414ccdeacc`  
		Last Modified: Wed, 15 Jun 2016 21:09:26 GMT  
		Size: 1.8 KB (1755 bytes)
	-	`sha256:560eed1016d692dc2ea55efd10bc4c50d96f234b003c375b110210a853bab6a1`  
		Last Modified: Wed, 15 Jun 2016 21:09:26 GMT  
		Size: 128.0 B
	-	`sha256:50d628eea821a18dc223c62bc57211d4e2a2dbba90bb475b56204603937f0a58`  
		Last Modified: Wed, 15 Jun 2016 21:09:26 GMT  
		Size: 7.5 KB (7536 bytes)

## `php:5.5.36-fpm-alpine`

```console
$ docker pull php@sha256:8199ef7b811d1441cf012b2b571ba50ba704d4cc54627de9974160b07af47ca9
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **30.7 MB (30694069 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1a2d2a86253d5612f380e0082108716bad0078dec5abdff5f7daf039d8c0167e`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 17:09:22 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Wed, 08 Jun 2016 17:09:22 GMT
ENV PHP_VERSION=5.5.36
# Wed, 08 Jun 2016 17:09:22 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Wed, 08 Jun 2016 17:09:22 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Wed, 08 Jun 2016 17:14:47 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:51 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:52 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:53 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:54 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:54 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:c957c930f391b445e58cb5a79f9569f7448339e54d99ff57ee24f52a50cd6774`  
		Last Modified: Wed, 08 Jun 2016 21:58:30 GMT  
		Size: 27.7 MB (27650141 bytes)
	-	`sha256:900ea839a51704eb225c73124942c71fc38f5fb4a974234007493c71c8175ecd`  
		Last Modified: Wed, 15 Jun 2016 21:10:01 GMT  
		Size: 1.7 KB (1745 bytes)
	-	`sha256:d285ec6e5ad00f4e9dd0d8deb349dd964d8004b20124bb7c7a0371cc53720315`  
		Last Modified: Wed, 15 Jun 2016 21:10:01 GMT  
		Size: 127.0 B
	-	`sha256:29e05533fd1b9f5dc5558499e433ef2eeac80367aafd7ec7967e5b2c506611ff`  
		Last Modified: Wed, 15 Jun 2016 21:10:01 GMT  
		Size: 7.5 KB (7525 bytes)

## `php:5.5-fpm-alpine`

```console
$ docker pull php@sha256:8199ef7b811d1441cf012b2b571ba50ba704d4cc54627de9974160b07af47ca9
```

-	Platforms:
	-	linux; amd64

### `php:5.5-fpm-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **30.7 MB (30694069 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1a2d2a86253d5612f380e0082108716bad0078dec5abdff5f7daf039d8c0167e`
-	Default Command: `["php-fpm"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:09:21 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-fpm --with-fpm-user=www-data --with-fpm-group=www-data
# Wed, 08 Jun 2016 17:09:22 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Wed, 08 Jun 2016 17:09:22 GMT
ENV PHP_VERSION=5.5.36
# Wed, 08 Jun 2016 17:09:22 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Wed, 08 Jun 2016 17:09:22 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Wed, 08 Jun 2016 17:14:47 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:51 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:52 GMT
WORKDIR /var/www/html
# Wed, 15 Jun 2016 21:00:53 GMT
RUN set -ex 	&& cd /usr/local/etc 	&& if [ -d php-fpm.d ]; then 		sed 's!=NONE/!=!g' php-fpm.conf.default | tee php-fpm.conf > /dev/null; 		cp php-fpm.d/www.conf.default php-fpm.d/www.conf; 	else 		mkdir php-fpm.d; 		cp php-fpm.conf.default php-fpm.d/www.conf; 		{ 			echo '[global]'; 			echo 'include=etc/php-fpm.d/*.conf'; 		} | tee php-fpm.conf; 	fi 	&& { 		echo '[global]'; 		echo 'error_log = /proc/self/fd/2'; 		echo; 		echo '[www]'; 		echo '; if we send this to /proc/self/fd/1, it never appears'; 		echo 'access.log = /proc/self/fd/2'; 		echo; 		echo 'clear_env = no'; 		echo; 		echo '; Ensure worker stdout and stderr are sent to the main error log.'; 		echo 'catch_workers_output = yes'; 	} | tee php-fpm.d/docker.conf 	&& { 		echo '[global]'; 		echo 'daemonize = no'; 		echo; 		echo '[www]'; 		echo 'listen = [::]:9000'; 	} | tee php-fpm.d/zz-docker.conf
# Wed, 15 Jun 2016 21:00:54 GMT
EXPOSE 9000/tcp
# Wed, 15 Jun 2016 21:00:54 GMT
CMD ["php-fpm"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:c957c930f391b445e58cb5a79f9569f7448339e54d99ff57ee24f52a50cd6774`  
		Last Modified: Wed, 08 Jun 2016 21:58:30 GMT  
		Size: 27.7 MB (27650141 bytes)
	-	`sha256:900ea839a51704eb225c73124942c71fc38f5fb4a974234007493c71c8175ecd`  
		Last Modified: Wed, 15 Jun 2016 21:10:01 GMT  
		Size: 1.7 KB (1745 bytes)
	-	`sha256:d285ec6e5ad00f4e9dd0d8deb349dd964d8004b20124bb7c7a0371cc53720315`  
		Last Modified: Wed, 15 Jun 2016 21:10:01 GMT  
		Size: 127.0 B
	-	`sha256:29e05533fd1b9f5dc5558499e433ef2eeac80367aafd7ec7967e5b2c506611ff`  
		Last Modified: Wed, 15 Jun 2016 21:10:01 GMT  
		Size: 7.5 KB (7525 bytes)

## `php:5.5.36-zts`

```console
$ docker pull php@sha256:ef4c95e350a8dffba1efb38fc71ecef4f4434005e693698507781968441cede6
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.1 MB (151098843 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c3b3f20482b79f35a60e1dfa63ab9e2fb2186d4596983528e9877d908ca6be45`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 03:46:00 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:46:00 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:46:00 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:46:00 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:52:37 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:56 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:56 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:f3cfa8edb92380c9dfcc89e732c8e5df6f72e4c5c4f123c0d443c5e5849a5328`  
		Last Modified: Wed, 15 Jun 2016 21:10:34 GMT  
		Size: 22.4 MB (22400967 bytes)
	-	`sha256:3112919604826bdf8d5b1b6a3093962a71256a7d62a515b5bb4d71304e71b111`  
		Last Modified: Wed, 15 Jun 2016 21:10:17 GMT  
		Size: 1.8 KB (1756 bytes)

## `php:5.5-zts`

```console
$ docker pull php@sha256:ef4c95e350a8dffba1efb38fc71ecef4f4434005e693698507781968441cede6
```

-	Platforms:
	-	linux; amd64

### `php:5.5-zts` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **151.1 MB (151098843 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c3b3f20482b79f35a60e1dfa63ab9e2fb2186d4596983528e9877d908ca6be45`
-	Default Command: `["php","-a"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Fri, 10 Jun 2016 02:34:30 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkg-config 		re2c
# Fri, 10 Jun 2016 02:35:57 GMT
RUN apt-get update && apt-get install -y 		$PHPIZE_DEPS 		ca-certificates 		curl 		libedit2 		libsqlite3-0 		libxml2 	--no-install-recommends && rm -r /var/lib/apt/lists/*
# Fri, 10 Jun 2016 02:35:58 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Fri, 10 Jun 2016 02:35:59 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Fri, 10 Jun 2016 02:55:58 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Fri, 10 Jun 2016 03:46:00 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Fri, 10 Jun 2016 03:46:00 GMT
ENV PHP_VERSION=5.5.36
# Fri, 10 Jun 2016 03:46:00 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Fri, 10 Jun 2016 03:46:00 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Fri, 10 Jun 2016 03:52:37 GMT
RUN set -xe 	&& buildDeps=" 		$PHP_EXTRA_BUILD_DEPS 		libcurl4-openssl-dev 		libedit-dev 		libsqlite3-dev 		libssl-dev 		libxml2-dev 		xz-utils 	" 	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src/php 	&& tar -xf "$PHP_FILENAME" -C /usr/src/php --strip-components=1 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(nproc)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -executable -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false -o APT::AutoRemove::SuggestsImportant=false $buildDeps
# Wed, 15 Jun 2016 21:00:56 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:56 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:357b76a4983822c380125e911928d20bf853d3a4ca869181c757d855408a9c90`  
		Last Modified: Tue, 14 Jun 2016 21:44:40 GMT  
		Size: 77.3 MB (77343405 bytes)
	-	`sha256:0e87614c69f0ba521d6a89ea9b82a5712ff209dfa89e14b1fef8be2056d5680d`  
		Last Modified: Tue, 14 Jun 2016 21:44:12 GMT  
		Size: 180.0 B
	-	`sha256:f3cfa8edb92380c9dfcc89e732c8e5df6f72e4c5c4f123c0d443c5e5849a5328`  
		Last Modified: Wed, 15 Jun 2016 21:10:34 GMT  
		Size: 22.4 MB (22400967 bytes)
	-	`sha256:3112919604826bdf8d5b1b6a3093962a71256a7d62a515b5bb4d71304e71b111`  
		Last Modified: Wed, 15 Jun 2016 21:10:17 GMT  
		Size: 1.8 KB (1756 bytes)

## `php:5.5.36-zts-alpine`

```console
$ docker pull php@sha256:71d8e2ea9bc245dbdfe6ba98b3ea24298ed8bad1d95ad505128f54001f41c602
```

-	Platforms:
	-	linux; amd64

### `php:5.5.36-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.1 MB (27138070 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:be4473276981aca1a1b0c2d17c77b0a9a30b4e177f933ccf534d98b456a813a4`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 17:21:29 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Wed, 08 Jun 2016 17:21:30 GMT
ENV PHP_VERSION=5.5.36
# Wed, 08 Jun 2016 17:21:30 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Wed, 08 Jun 2016 17:21:30 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Wed, 08 Jun 2016 17:27:06 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:1e76c9edbdb766c7428be9b722dccd9deb199fd85e8b7ba7f8bdb7615d471ade`  
		Last Modified: Wed, 08 Jun 2016 21:59:33 GMT  
		Size: 24.1 MB (24101791 bytes)
	-	`sha256:0c230f08bba686e54df79a183e1992bf7f56680392c231b7103247ea9b4d6dbc`  
		Last Modified: Wed, 15 Jun 2016 21:10:48 GMT  
		Size: 1.7 KB (1748 bytes)

## `php:5.5-zts-alpine`

```console
$ docker pull php@sha256:71d8e2ea9bc245dbdfe6ba98b3ea24298ed8bad1d95ad505128f54001f41c602
```

-	Platforms:
	-	linux; amd64

### `php:5.5-zts-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **27.1 MB (27138070 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:be4473276981aca1a1b0c2d17c77b0a9a30b4e177f933ccf534d98b456a813a4`
-	Default Command: `["php","-a"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Wed, 08 Jun 2016 16:50:57 GMT
ENV PHPIZE_DEPS=autoconf 		file 		g++ 		gcc 		libc-dev 		make 		pkgconf 		re2c
# Wed, 08 Jun 2016 16:51:00 GMT
RUN apk add --no-cache --virtual .persistent-deps 		ca-certificates 		curl
# Wed, 08 Jun 2016 16:51:01 GMT
RUN set -x 	&& addgroup -g 82 -S www-data 	&& adduser -u 82 -D -S -G www-data www-data
# Wed, 08 Jun 2016 16:51:01 GMT
ENV PHP_INI_DIR=/usr/local/etc/php
# Wed, 08 Jun 2016 16:51:02 GMT
RUN mkdir -p $PHP_INI_DIR/conf.d
# Wed, 08 Jun 2016 17:21:29 GMT
ENV PHP_EXTRA_CONFIGURE_ARGS=--enable-maintainer-zts
# Wed, 08 Jun 2016 17:21:29 GMT
ENV GPG_KEYS=0B96609E270F565C13292B24C13C70B87267B52D 0BD78B5F97500D450838F95DFE857D9A90D90EC1 F38252826ACD957EF380D39F2F7956BC5DA04B5D
# Wed, 08 Jun 2016 17:21:30 GMT
ENV PHP_VERSION=5.5.36
# Wed, 08 Jun 2016 17:21:30 GMT
ENV PHP_FILENAME=php-5.5.36.tar.xz
# Wed, 08 Jun 2016 17:21:30 GMT
ENV PHP_SHA256=e1bbe33d6b4da66b15c483131520a9fc505eeb6629fa70c5cfba79590a1d0801
# Wed, 08 Jun 2016 17:27:06 GMT
RUN set -xe 	&& apk add --no-cache --virtual .build-deps 		$PHPIZE_DEPS 		curl-dev 		gnupg 		libedit-dev 		libxml2-dev 		openssl-dev 		sqlite-dev 	&& curl -fSL "http://php.net/get/$PHP_FILENAME/from/this/mirror" -o "$PHP_FILENAME" 	&& echo "$PHP_SHA256 *$PHP_FILENAME" | sha256sum -c - 	&& curl -fSL "http://php.net/get/$PHP_FILENAME.asc/from/this/mirror" -o "$PHP_FILENAME.asc" 	&& export GNUPGHOME="$(mktemp -d)" 	&& for key in $GPG_KEYS; do 		gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"; 	done 	&& gpg --batch --verify "$PHP_FILENAME.asc" "$PHP_FILENAME" 	&& rm -r "$GNUPGHOME" "$PHP_FILENAME.asc" 	&& mkdir -p /usr/src 	&& tar -Jxf "$PHP_FILENAME" -C /usr/src 	&& mv "/usr/src/php-$PHP_VERSION" /usr/src/php 	&& rm "$PHP_FILENAME" 	&& cd /usr/src/php 	&& ./configure 		--with-config-file-path="$PHP_INI_DIR" 		--with-config-file-scan-dir="$PHP_INI_DIR/conf.d" 		$PHP_EXTRA_CONFIGURE_ARGS 		--disable-cgi 		--enable-mysqlnd 		--enable-mbstring 		--with-curl 		--with-libedit 		--with-openssl 		--with-zlib 	&& make -j"$(getconf _NPROCESSORS_ONLN)" 	&& make install 	&& { find /usr/local/bin /usr/local/sbin -type f -perm +0111 -exec strip --strip-all '{}' + || true; } 	&& make clean 	&& runDeps="$( 		scanelf --needed --nobanner --recursive /usr/local 			| awk '{ gsub(/,/, "\nso:", $2); print "so:" $2 }' 			| sort -u 			| xargs -r apk info --installed 			| sort -u 	)" 	&& apk add --no-cache --virtual .php-rundeps $runDeps 	&& apk del .build-deps
# Wed, 15 Jun 2016 21:00:58 GMT
COPY multi:a8819301efc7ce6569bcf183723931153c5b968224bce96498ddbabe72ce7eaa in /usr/local/bin/
# Wed, 15 Jun 2016 21:00:58 GMT
CMD ["php" "-a"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:abe5017ce7f3268fc438c66603e2ef5a88c2c9ae8fdbda12c17ef574f1241170`  
		Last Modified: Wed, 08 Jun 2016 21:56:30 GMT  
		Size: 701.9 KB (701861 bytes)
	-	`sha256:d45f978624457119d329668d25bbcf21d3e6e749ccd9a1d28fffc91b308ea5e7`  
		Last Modified: Wed, 08 Jun 2016 21:56:31 GMT  
		Size: 22.2 KB (22230 bytes)
	-	`sha256:e07af867184ff33cba0749797b60b96f234d6513e623f967fdd09002a80c86c1`  
		Last Modified: Wed, 08 Jun 2016 21:56:29 GMT  
		Size: 168.0 B
	-	`sha256:1e76c9edbdb766c7428be9b722dccd9deb199fd85e8b7ba7f8bdb7615d471ade`  
		Last Modified: Wed, 08 Jun 2016 21:59:33 GMT  
		Size: 24.1 MB (24101791 bytes)
	-	`sha256:0c230f08bba686e54df79a183e1992bf7f56680392c231b7103247ea9b4d6dbc`  
		Last Modified: Wed, 15 Jun 2016 21:10:48 GMT  
		Size: 1.7 KB (1748 bytes)
