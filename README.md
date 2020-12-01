<h1 align=center>Dockette / Web</h1>

<p align=center>
   🐳 Ready-to-use docker images for websites (nginx, PHP 7.2/7.3/7.4 + FPM, supervisor).
</p>

<p align=center>
🕹 <a href="https://f3l1x.io">f3l1x.io</a> | 💻 <a href="https://github.com/f3l1x">f3l1x</a> | 🐦 <a href="https://twitter.com/xf3l1x">@xf3l1x</a>
</p>

<p align=center>
	<a href="https://hub.docker.com/r/dockette/web/"><img src="https://img.shields.io/docker/stars/dockette/web.svg?style=flat"></a>
	<a href="https://hub.docker.com/r/dockette/web/"><img src="https://img.shields.io/docker/pulls/dockette/web.svg?style=flat"></a>
</p>

![](https://github.com/dockette/web/blob/master/screenshot.png "It works")

## Usage

| Image                 | Distro | PHP |
|-----------------------|--------|-----|
| `dockette/web:php-74` | Buster | 7.4 |
| `dockette/web:php-73` | Buster | 7.3 |
| `dockette/web:php-72` | Buster | 7.2 |

You can easily start your Docker container with following command.

```
docker run \
	-it \
	--rm \
	--name www \
	-p 80:80 \
	dockette/web:php74
```

## Development

See [how to contribute](https://contributte.org/contributing.html) to this package.

This package is currently maintaining by these authors.

<a href="https://github.com/f3l1x">
    <img width="80" height="80" src="https://avatars2.githubusercontent.com/u/538058?v=3&s=80">
</a>

-----

Consider to [support](https://contributte.org/partners.html) **dockette** development team.
Also thank you for using this package.
