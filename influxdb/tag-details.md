<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `influxdb`

-	[`influxdb:0.12`](#influxdb012)
-	[`influxdb:0.12.2`](#influxdb0122)
-	[`influxdb:0.13`](#influxdb013)
-	[`influxdb:0.13.0`](#influxdb0130)
-	[`influxdb:latest`](#influxdblatest)
-	[`influxdb:0.13-alpine`](#influxdb013-alpine)
-	[`influxdb:0.13.0-alpine`](#influxdb0130-alpine)
-	[`influxdb:alpine`](#influxdbalpine)
-	[`influxdb:1.0.0-beta1`](#influxdb100-beta1)
-	[`influxdb:1.0.0-beta1-alpine`](#influxdb100-beta1-alpine)

## `influxdb:0.12`

```console
$ docker pull influxdb@sha256:2ca85887cc062a835017062b664a9fe7021d1bd0a7674bebdfe426f0a21efdec
```

-	Platforms:
	-	linux; amd64

### `influxdb:0.12` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **84.6 MB (84599798 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:3293e4a66554e2ee9ddd1765faf204dc04dd239e3d33feb9a02f9537a081f2c7`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 22:54:46 GMT
RUN gpg     --keyserver hkp://ha.pool.sks-keyservers.net     --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5
# Thu, 09 Jun 2016 22:55:32 GMT
ENV INFLUXDB_VERSION=0.12.2
# Thu, 09 Jun 2016 22:55:37 GMT
RUN wget -q https://s3.amazonaws.com/influxdb/influxdb_$INFLUXDB_VERSION-1_amd64.deb.asc &&     wget -q https://s3.amazonaws.com/influxdb/influxdb_$INFLUXDB_VERSION-1_amd64.deb &&     gpg --batch --verify influxdb_$INFLUXDB_VERSION-1_amd64.deb.asc influxdb_$INFLUXDB_VERSION-1_amd64.deb &&     dpkg -i influxdb_$INFLUXDB_VERSION-1_amd64.deb &&     rm -f influxdb_$INFLUXDB_VERSION-1_amd64.deb*
# Thu, 09 Jun 2016 22:55:38 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:55:38 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:55:39 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:55:39 GMT
COPY file:922a826f6063efc5079d9a5638b49bc5dd43860c8245351b750a74e5a126763d in /entrypoint.sh
# Thu, 09 Jun 2016 22:55:39 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:55:40 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:62a96cb5d4e863956fddb512db1b13b66e74fc050a6fcb6e97970a3a76d97b0d`  
		Last Modified: Thu, 09 Jun 2016 22:55:03 GMT  
		Size: 6.8 KB (6755 bytes)
	-	`sha256:2c751d777117ba972c45cc34b460a984bbeb0de654412d5457f7fca25bea3d20`  
		Last Modified: Thu, 09 Jun 2016 22:56:51 GMT  
		Size: 14.7 MB (14692728 bytes)
	-	`sha256:304d964efe8acaddff19a31eea0e7ceef170d8ff893195156952f5fda6f97e7d`  
		Last Modified: Thu, 09 Jun 2016 22:56:43 GMT  
		Size: 240.0 B
	-	`sha256:c665d4020ec349c2cc8996e2338f097933ef8334fd0ff4051cd1f72c25505e1f`  
		Last Modified: Thu, 09 Jun 2016 22:56:43 GMT  
		Size: 321.0 B

## `influxdb:0.12.2`

```console
$ docker pull influxdb@sha256:2ca85887cc062a835017062b664a9fe7021d1bd0a7674bebdfe426f0a21efdec
```

-	Platforms:
	-	linux; amd64

### `influxdb:0.12.2` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **84.6 MB (84599798 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:3293e4a66554e2ee9ddd1765faf204dc04dd239e3d33feb9a02f9537a081f2c7`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 22:54:46 GMT
RUN gpg     --keyserver hkp://ha.pool.sks-keyservers.net     --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5
# Thu, 09 Jun 2016 22:55:32 GMT
ENV INFLUXDB_VERSION=0.12.2
# Thu, 09 Jun 2016 22:55:37 GMT
RUN wget -q https://s3.amazonaws.com/influxdb/influxdb_$INFLUXDB_VERSION-1_amd64.deb.asc &&     wget -q https://s3.amazonaws.com/influxdb/influxdb_$INFLUXDB_VERSION-1_amd64.deb &&     gpg --batch --verify influxdb_$INFLUXDB_VERSION-1_amd64.deb.asc influxdb_$INFLUXDB_VERSION-1_amd64.deb &&     dpkg -i influxdb_$INFLUXDB_VERSION-1_amd64.deb &&     rm -f influxdb_$INFLUXDB_VERSION-1_amd64.deb*
# Thu, 09 Jun 2016 22:55:38 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:55:38 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:55:39 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:55:39 GMT
COPY file:922a826f6063efc5079d9a5638b49bc5dd43860c8245351b750a74e5a126763d in /entrypoint.sh
# Thu, 09 Jun 2016 22:55:39 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:55:40 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:62a96cb5d4e863956fddb512db1b13b66e74fc050a6fcb6e97970a3a76d97b0d`  
		Last Modified: Thu, 09 Jun 2016 22:55:03 GMT  
		Size: 6.8 KB (6755 bytes)
	-	`sha256:2c751d777117ba972c45cc34b460a984bbeb0de654412d5457f7fca25bea3d20`  
		Last Modified: Thu, 09 Jun 2016 22:56:51 GMT  
		Size: 14.7 MB (14692728 bytes)
	-	`sha256:304d964efe8acaddff19a31eea0e7ceef170d8ff893195156952f5fda6f97e7d`  
		Last Modified: Thu, 09 Jun 2016 22:56:43 GMT  
		Size: 240.0 B
	-	`sha256:c665d4020ec349c2cc8996e2338f097933ef8334fd0ff4051cd1f72c25505e1f`  
		Last Modified: Thu, 09 Jun 2016 22:56:43 GMT  
		Size: 321.0 B

## `influxdb:0.13`

```console
$ docker pull influxdb@sha256:5f726b18bd7cf2a9f0edab66578fa64ad1a261b4cc321591262addf78a9c30b7
```

-	Platforms:
	-	linux; amd64

### `influxdb:0.13` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **88.1 MB (88076369 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:282a1f3d7e830a2ee3f6c38aeb9afb82dd4ac78e21b91118e09206d83d879f5e`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 22:54:46 GMT
RUN gpg     --keyserver hkp://ha.pool.sks-keyservers.net     --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5
# Thu, 09 Jun 2016 22:55:41 GMT
ENV INFLUXDB_VERSION=0.13.0
# Thu, 09 Jun 2016 22:55:44 GMT
RUN wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb &&     gpg --batch --verify influxdb_${INFLUXDB_VERSION}_amd64.deb.asc influxdb_${INFLUXDB_VERSION}_amd64.deb &&     dpkg -i influxdb_${INFLUXDB_VERSION}_amd64.deb &&     rm -f influxdb_${INFLUXDB_VERSION}_amd64.deb*
# Thu, 09 Jun 2016 22:55:45 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:55:45 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:55:46 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:55:46 GMT
COPY file:812647bc923fb58bd6fba201df6d23a9311547ea81f3a598e86e2b93b2399169 in /entrypoint.sh
# Thu, 09 Jun 2016 22:55:47 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:55:47 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:62a96cb5d4e863956fddb512db1b13b66e74fc050a6fcb6e97970a3a76d97b0d`  
		Last Modified: Thu, 09 Jun 2016 22:55:03 GMT  
		Size: 6.8 KB (6755 bytes)
	-	`sha256:7df308bfe7dd08b1f1689995660a5b6ca661a1cce31a64eec7c05a37c4b25ee1`  
		Last Modified: Thu, 09 Jun 2016 22:57:11 GMT  
		Size: 18.2 MB (18169435 bytes)
	-	`sha256:f184d8a590b0f0858d63bfb53b32a43bb956fab5e7bac254934c67cce196d75d`  
		Last Modified: Thu, 09 Jun 2016 22:57:03 GMT  
		Size: 239.0 B
	-	`sha256:d4bce7467b0cc82fdc9db9bd918fbfb056aa0f653644957994c822761e941614`  
		Last Modified: Thu, 09 Jun 2016 22:57:04 GMT  
		Size: 186.0 B

## `influxdb:0.13.0`

```console
$ docker pull influxdb@sha256:5f726b18bd7cf2a9f0edab66578fa64ad1a261b4cc321591262addf78a9c30b7
```

-	Platforms:
	-	linux; amd64

### `influxdb:0.13.0` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **88.1 MB (88076369 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:282a1f3d7e830a2ee3f6c38aeb9afb82dd4ac78e21b91118e09206d83d879f5e`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 22:54:46 GMT
RUN gpg     --keyserver hkp://ha.pool.sks-keyservers.net     --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5
# Thu, 09 Jun 2016 22:55:41 GMT
ENV INFLUXDB_VERSION=0.13.0
# Thu, 09 Jun 2016 22:55:44 GMT
RUN wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb &&     gpg --batch --verify influxdb_${INFLUXDB_VERSION}_amd64.deb.asc influxdb_${INFLUXDB_VERSION}_amd64.deb &&     dpkg -i influxdb_${INFLUXDB_VERSION}_amd64.deb &&     rm -f influxdb_${INFLUXDB_VERSION}_amd64.deb*
# Thu, 09 Jun 2016 22:55:45 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:55:45 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:55:46 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:55:46 GMT
COPY file:812647bc923fb58bd6fba201df6d23a9311547ea81f3a598e86e2b93b2399169 in /entrypoint.sh
# Thu, 09 Jun 2016 22:55:47 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:55:47 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:62a96cb5d4e863956fddb512db1b13b66e74fc050a6fcb6e97970a3a76d97b0d`  
		Last Modified: Thu, 09 Jun 2016 22:55:03 GMT  
		Size: 6.8 KB (6755 bytes)
	-	`sha256:7df308bfe7dd08b1f1689995660a5b6ca661a1cce31a64eec7c05a37c4b25ee1`  
		Last Modified: Thu, 09 Jun 2016 22:57:11 GMT  
		Size: 18.2 MB (18169435 bytes)
	-	`sha256:f184d8a590b0f0858d63bfb53b32a43bb956fab5e7bac254934c67cce196d75d`  
		Last Modified: Thu, 09 Jun 2016 22:57:03 GMT  
		Size: 239.0 B
	-	`sha256:d4bce7467b0cc82fdc9db9bd918fbfb056aa0f653644957994c822761e941614`  
		Last Modified: Thu, 09 Jun 2016 22:57:04 GMT  
		Size: 186.0 B

## `influxdb:latest`

```console
$ docker pull influxdb@sha256:5f726b18bd7cf2a9f0edab66578fa64ad1a261b4cc321591262addf78a9c30b7
```

-	Platforms:
	-	linux; amd64

### `influxdb:latest` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **88.1 MB (88076369 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:282a1f3d7e830a2ee3f6c38aeb9afb82dd4ac78e21b91118e09206d83d879f5e`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 22:54:46 GMT
RUN gpg     --keyserver hkp://ha.pool.sks-keyservers.net     --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5
# Thu, 09 Jun 2016 22:55:41 GMT
ENV INFLUXDB_VERSION=0.13.0
# Thu, 09 Jun 2016 22:55:44 GMT
RUN wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb &&     gpg --batch --verify influxdb_${INFLUXDB_VERSION}_amd64.deb.asc influxdb_${INFLUXDB_VERSION}_amd64.deb &&     dpkg -i influxdb_${INFLUXDB_VERSION}_amd64.deb &&     rm -f influxdb_${INFLUXDB_VERSION}_amd64.deb*
# Thu, 09 Jun 2016 22:55:45 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:55:45 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:55:46 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:55:46 GMT
COPY file:812647bc923fb58bd6fba201df6d23a9311547ea81f3a598e86e2b93b2399169 in /entrypoint.sh
# Thu, 09 Jun 2016 22:55:47 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:55:47 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:62a96cb5d4e863956fddb512db1b13b66e74fc050a6fcb6e97970a3a76d97b0d`  
		Last Modified: Thu, 09 Jun 2016 22:55:03 GMT  
		Size: 6.8 KB (6755 bytes)
	-	`sha256:7df308bfe7dd08b1f1689995660a5b6ca661a1cce31a64eec7c05a37c4b25ee1`  
		Last Modified: Thu, 09 Jun 2016 22:57:11 GMT  
		Size: 18.2 MB (18169435 bytes)
	-	`sha256:f184d8a590b0f0858d63bfb53b32a43bb956fab5e7bac254934c67cce196d75d`  
		Last Modified: Thu, 09 Jun 2016 22:57:03 GMT  
		Size: 239.0 B
	-	`sha256:d4bce7467b0cc82fdc9db9bd918fbfb056aa0f653644957994c822761e941614`  
		Last Modified: Thu, 09 Jun 2016 22:57:04 GMT  
		Size: 186.0 B

## `influxdb:0.13-alpine`

```console
$ docker pull influxdb@sha256:dd6a4d16330c79d7685ca7b5352fab9a3a9dad69fb40ac7faed565f2f7d39eb6
```

-	Platforms:
	-	linux; amd64

### `influxdb:0.13-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **15.8 MB (15838531 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a5596303648db4795bd140e8c71bab8806f39a89f687bd2ec1a165125af78869`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Thu, 09 Jun 2016 22:55:48 GMT
ENV INFLUXDB_VERSION=0.13.0
# Thu, 09 Jun 2016 22:56:07 GMT
RUN apk add --no-cache --virtual .build-deps wget gnupg tar ca-certificates &&     update-ca-certificates &&     gpg --keyserver hkp://ha.pool.sks-keyservers.net         --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5 &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     gpg --batch --verify influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     mkdir -p /usr/src &&     tar -C /usr/src -xzf influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     rm -f /usr/src/influxdb-*/influxdb.conf &&     chmod +x /usr/src/influxdb-*/* &&     cp -a /usr/src/influxdb-*/* /usr/bin/ &&     rm -rf *.tar.gz* /usr/src /root/.gnupg &&     apk del .build-deps
# Thu, 09 Jun 2016 22:56:07 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:56:08 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:56:08 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:56:09 GMT
COPY file:69ba622c5d14acee69909e208de64bf13aa81f0010ff82238c8825ba99d65290 in /entrypoint.sh
# Thu, 09 Jun 2016 22:56:09 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:56:10 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:a7b68a60573a4528e501dc3dfff14fc461c8b7b0fe22689fed1fbc63ff1fe43a`  
		Last Modified: Thu, 09 Jun 2016 22:57:33 GMT  
		Size: 13.5 MB (13527834 bytes)
	-	`sha256:424534287749607d8aa784837f1f5c8cd09b5e56def8cfad68fefec12cb858be`  
		Last Modified: Thu, 09 Jun 2016 22:57:28 GMT  
		Size: 242.0 B
	-	`sha256:ca3a099144e09071a684bde83c62e33588e7b934e02ad8f7b3f7eb477b90c51d`  
		Last Modified: Thu, 09 Jun 2016 22:57:28 GMT  
		Size: 183.0 B

## `influxdb:0.13.0-alpine`

```console
$ docker pull influxdb@sha256:dd6a4d16330c79d7685ca7b5352fab9a3a9dad69fb40ac7faed565f2f7d39eb6
```

-	Platforms:
	-	linux; amd64

### `influxdb:0.13.0-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **15.8 MB (15838531 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a5596303648db4795bd140e8c71bab8806f39a89f687bd2ec1a165125af78869`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Thu, 09 Jun 2016 22:55:48 GMT
ENV INFLUXDB_VERSION=0.13.0
# Thu, 09 Jun 2016 22:56:07 GMT
RUN apk add --no-cache --virtual .build-deps wget gnupg tar ca-certificates &&     update-ca-certificates &&     gpg --keyserver hkp://ha.pool.sks-keyservers.net         --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5 &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     gpg --batch --verify influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     mkdir -p /usr/src &&     tar -C /usr/src -xzf influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     rm -f /usr/src/influxdb-*/influxdb.conf &&     chmod +x /usr/src/influxdb-*/* &&     cp -a /usr/src/influxdb-*/* /usr/bin/ &&     rm -rf *.tar.gz* /usr/src /root/.gnupg &&     apk del .build-deps
# Thu, 09 Jun 2016 22:56:07 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:56:08 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:56:08 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:56:09 GMT
COPY file:69ba622c5d14acee69909e208de64bf13aa81f0010ff82238c8825ba99d65290 in /entrypoint.sh
# Thu, 09 Jun 2016 22:56:09 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:56:10 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:a7b68a60573a4528e501dc3dfff14fc461c8b7b0fe22689fed1fbc63ff1fe43a`  
		Last Modified: Thu, 09 Jun 2016 22:57:33 GMT  
		Size: 13.5 MB (13527834 bytes)
	-	`sha256:424534287749607d8aa784837f1f5c8cd09b5e56def8cfad68fefec12cb858be`  
		Last Modified: Thu, 09 Jun 2016 22:57:28 GMT  
		Size: 242.0 B
	-	`sha256:ca3a099144e09071a684bde83c62e33588e7b934e02ad8f7b3f7eb477b90c51d`  
		Last Modified: Thu, 09 Jun 2016 22:57:28 GMT  
		Size: 183.0 B

## `influxdb:alpine`

```console
$ docker pull influxdb@sha256:dd6a4d16330c79d7685ca7b5352fab9a3a9dad69fb40ac7faed565f2f7d39eb6
```

-	Platforms:
	-	linux; amd64

### `influxdb:alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **15.8 MB (15838531 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a5596303648db4795bd140e8c71bab8806f39a89f687bd2ec1a165125af78869`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Thu, 09 Jun 2016 22:55:48 GMT
ENV INFLUXDB_VERSION=0.13.0
# Thu, 09 Jun 2016 22:56:07 GMT
RUN apk add --no-cache --virtual .build-deps wget gnupg tar ca-certificates &&     update-ca-certificates &&     gpg --keyserver hkp://ha.pool.sks-keyservers.net         --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5 &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     gpg --batch --verify influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     mkdir -p /usr/src &&     tar -C /usr/src -xzf influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     rm -f /usr/src/influxdb-*/influxdb.conf &&     chmod +x /usr/src/influxdb-*/* &&     cp -a /usr/src/influxdb-*/* /usr/bin/ &&     rm -rf *.tar.gz* /usr/src /root/.gnupg &&     apk del .build-deps
# Thu, 09 Jun 2016 22:56:07 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:56:08 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:56:08 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:56:09 GMT
COPY file:69ba622c5d14acee69909e208de64bf13aa81f0010ff82238c8825ba99d65290 in /entrypoint.sh
# Thu, 09 Jun 2016 22:56:09 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:56:10 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:a7b68a60573a4528e501dc3dfff14fc461c8b7b0fe22689fed1fbc63ff1fe43a`  
		Last Modified: Thu, 09 Jun 2016 22:57:33 GMT  
		Size: 13.5 MB (13527834 bytes)
	-	`sha256:424534287749607d8aa784837f1f5c8cd09b5e56def8cfad68fefec12cb858be`  
		Last Modified: Thu, 09 Jun 2016 22:57:28 GMT  
		Size: 242.0 B
	-	`sha256:ca3a099144e09071a684bde83c62e33588e7b934e02ad8f7b3f7eb477b90c51d`  
		Last Modified: Thu, 09 Jun 2016 22:57:28 GMT  
		Size: 183.0 B

## `influxdb:1.0.0-beta1`

```console
$ docker pull influxdb@sha256:03cf92ea0e25e2c31f66888d1d17ebf4e206e8cf9e6b5555d33c05aa3038e1f3
```

-	Platforms:
	-	linux; amd64

### `influxdb:1.0.0-beta1` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **89.0 MB (88961158 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:47529a135336f38de29699ff9dc3085e98e2f3d6adfdad0cf6181d6ab81613f5`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 22:54:46 GMT
RUN gpg     --keyserver hkp://ha.pool.sks-keyservers.net     --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5
# Thu, 09 Jun 2016 22:56:11 GMT
ENV INFLUXDB_VERSION=1.0.0-beta1
# Thu, 09 Jun 2016 22:56:15 GMT
RUN wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb_${INFLUXDB_VERSION}_amd64.deb &&     gpg --batch --verify influxdb_${INFLUXDB_VERSION}_amd64.deb.asc influxdb_${INFLUXDB_VERSION}_amd64.deb &&     dpkg -i influxdb_${INFLUXDB_VERSION}_amd64.deb &&     rm -f influxdb_${INFLUXDB_VERSION}_amd64.deb*
# Thu, 09 Jun 2016 22:56:16 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:56:16 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:56:17 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:56:17 GMT
COPY file:812647bc923fb58bd6fba201df6d23a9311547ea81f3a598e86e2b93b2399169 in /entrypoint.sh
# Thu, 09 Jun 2016 22:56:18 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:56:18 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:62a96cb5d4e863956fddb512db1b13b66e74fc050a6fcb6e97970a3a76d97b0d`  
		Last Modified: Thu, 09 Jun 2016 22:55:03 GMT  
		Size: 6.8 KB (6755 bytes)
	-	`sha256:c52177100652cce28284af0fee063a22bc558782671f3cd1dc0c21419f6bea0d`  
		Last Modified: Thu, 09 Jun 2016 22:57:56 GMT  
		Size: 19.1 MB (19054226 bytes)
	-	`sha256:57e801c97f2c0a63b02224d914aaff67cc1012e55fc917804142ce91918304c4`  
		Last Modified: Thu, 09 Jun 2016 22:57:48 GMT  
		Size: 239.0 B
	-	`sha256:7a9378ddcb5888050495ad70e9d521a532f61d30123dd918b0be65caefd71f2d`  
		Last Modified: Thu, 09 Jun 2016 22:57:48 GMT  
		Size: 184.0 B

## `influxdb:1.0.0-beta1-alpine`

```console
$ docker pull influxdb@sha256:70f7a7aba2088e876f6c33571b2926ce76816a414f96842102b67ce81e8d38fb
```

-	Platforms:
	-	linux; amd64

### `influxdb:1.0.0-beta1-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **16.5 MB (16511689 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:22839e2db1ab0dfe0563d8a25651c83287e303ddca3000545e4d70e38464937b`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["influxd"]`

```dockerfile
# Wed, 08 Jun 2016 00:48:01 GMT
ADD file:bca92e550bd2ce926584aef2032464b6ebf543ce69133b6602c781866165d703 in /
# Thu, 09 Jun 2016 22:56:19 GMT
ENV INFLUXDB_VERSION=1.0.0-beta1
# Thu, 09 Jun 2016 22:56:34 GMT
RUN apk add --no-cache --virtual .build-deps wget gnupg tar ca-certificates &&     update-ca-certificates &&     gpg --keyserver hkp://ha.pool.sks-keyservers.net         --recv-keys 05CE15085FC09D18E99EFB22684A14CF2582E0C5 &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc &&     wget -q https://dl.influxdata.com/influxdb/releases/influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     gpg --batch --verify influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz.asc influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     mkdir -p /usr/src &&     tar -C /usr/src -xzf influxdb-${INFLUXDB_VERSION}-static_linux_amd64.tar.gz &&     rm -f /usr/src/influxdb-*/influxdb.conf &&     chmod +x /usr/src/influxdb-*/* &&     cp -a /usr/src/influxdb-*/* /usr/bin/ &&     rm -rf *.tar.gz* /usr/src /root/.gnupg &&     apk del .build-deps
# Thu, 09 Jun 2016 22:56:35 GMT
COPY file:cbca5b2cb2c16f6d9b796839e1bcf66ed4b994c8837f985a80d2247e8161bcc7 in /etc/influxdb/influxdb.conf
# Thu, 09 Jun 2016 22:56:35 GMT
EXPOSE 8083/tcp 8086/tcp
# Thu, 09 Jun 2016 22:56:36 GMT
VOLUME [/var/lib/influxdb]
# Thu, 09 Jun 2016 22:56:36 GMT
COPY file:69ba622c5d14acee69909e208de64bf13aa81f0010ff82238c8825ba99d65290 in /entrypoint.sh
# Thu, 09 Jun 2016 22:56:37 GMT
ENTRYPOINT &{["/entrypoint.sh"]}
# Thu, 09 Jun 2016 22:56:37 GMT
CMD ["influxd"]
```

-	Layers:
	-	`sha256:fae91920dcd4542f97c9350b3157139a5d901362c2abec284de5ebd1b45b4957`  
		Last Modified: Thu, 02 Jun 2016 21:44:01 GMT  
		Size: 2.3 MB (2310272 bytes)
	-	`sha256:c84157958dd9eb5d3abba5c396454f96721b7d8327e937f3449c550289c0c219`  
		Last Modified: Thu, 09 Jun 2016 22:58:12 GMT  
		Size: 14.2 MB (14200996 bytes)
	-	`sha256:def940730e5aa73119ae1a72441c79917c02a68edb222da59134207fd3213f54`  
		Last Modified: Thu, 09 Jun 2016 22:58:05 GMT  
		Size: 239.0 B
	-	`sha256:4e56ae28de330747c736b9fe5523faafcb1a5918bd4d6bba29f35a197736bac6`  
		Last Modified: Thu, 09 Jun 2016 22:58:05 GMT  
		Size: 182.0 B
