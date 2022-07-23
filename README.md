# Sambungkata on Whatsapp Bot, Like on Telegram Bot

<a href="https://visitor-badge.glitch.me/badge?page_id=syahrularranger/sambungkata"><img title="Visitor" src="https://visitor-badge.glitch.me/badge?page_id=syahrularranger/sambungkata"></a>
<a href="https://github.com/syahrularranger/sambungkata/network/members"><img title="Forks" src="https://img.shields.io/github/forks/syahrularranger/sambungkata?label=Forks&color=blue&style=flat-square"></a>
<a href="https://github.com/syahrularranger/sambungkata/watchers"><img title="Watchers" src="https://img.shields.io/github/watchers/syahrularranger/sambungkata?label=Watchers&color=green&style=flat-square"></a>
<a href="https://github.com/syahrularranger/sambungkata/stargazers"><img title="Stars" src="https://img.shields.io/github/stars/syahrularranger/sambungkata?label=Stars&color=yellow&style=flat-square"></a>
<a href="https://github.com/syahrularranger/sambungkata/graphs/contributors"><img title="Contributors" src="https://img.shields.io/github/contributors/syahrularranger/sambungkata?label=Contributors&color=blue&style=flat-square"></a>
<a href="https://github.com/syahrularranger/sambungkata/issues"><img title="Issues" src="https://img.shields.io/github/issues/syahrularranger/sambungkata?label=Issues&color=success&style=flat-square"></a>
<a href="https://github.com/syahrularranger/sambungkata/issues?q=is%3Aissue+is%3Aclosed"><img title="Issues" src="https://img.shields.io/github/issues-closed/syahrularranger/sambungkata?label=Issues&color=red&style=flat-square"></a>
<a href="https://github.com/syahrularranger/sambungkata/pulls"><img title="Pull Request" src="https://img.shields.io/github/issues-pr/syahrularranger/sambungkata?label=PullRequest&color=success&style=flat-square"></a>
<a href="https://github.com/syahrularranger/sambungkata/pulls?q=is%3Apr+is%3Aclosed"><img title="Pull Request" src="https://img.shields.io/github/issues-pr-closed/syahrularranger/sambungkata?label=PullRequest&color=red&style=flat-square"></a>


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/syahrularranger/sambungkata)

## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)

```bash
git clone https://github.com/syahrularranger/sambungkata.git
cd sambungkata
npm i
node .
```

---------

## UNTUK PENGGUNA TERMUX

* Download Termux [`Klik Disini`](https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_universal.apk)

```
$ pkg update && upgrade -y
$ apt update && upgrade -y
$ pkg install nodejs-lts
$ pkg install git
$ git clone https://github.com/syahrularranger/sambungkata.git
$ cd sambungkata
$ npm i
$ node .
```
---------
## UNTUK PENGGUNA HEROKU

### Instal Buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/mcollina/heroku-buildpack-imagemagick.git

---------
## Arguments `node . [--options] [<session name>]` 

### `--session <nama file>`

menggunakan session dari nama file yang berbeda, default `session.data.json`

contoh nama file `levibot.json` maka penggunaannya `node . --session 'levibot'`

### `--prefix <prefix>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <url mongodb kamu>`

Buka file package.json dan isikan url mongodb kamu di bagian `mongo: --db url mongodb`!

### `--db <json-server-url>`

menggunakan db eksternal alih-alih db lokal, **disarankan** menggunakan mongodb

contoh server dengan mongodb `mongodb+srv://<username>:<password>@name-of-your-db.thhce.mongodb.net/myFirstDatabase?retryWrites=true&w=majority`

contoh server dengan repl `https://json-server.nurutomo.repl.co/`

kode: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

##### Special Thanks to
[![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo)

##### Base Multi-Device from
[![Fokus ID](https://github.com/fokusdotid.png?size=100)](https://github.com/fokusdotid)

##### Sambung kata Maker
[![Syahrul](https://github.com/syahrularranger.png?size=100)](https://github.com/syahrularranger)

#####  KBBI Scraper
[![Ariffb](https://github.com/ariffb25.png?size=100)](https://github.com/ariffb25)

