# \<ark-reader\>

Online Display of data extracted from ark save games
查看恐龙的信息

提取信息
```
java -jar ark-tools.jar tamed /home/steam/ARK/ShooterGame/Saved/SavedArks/TheIsland.ark /var/www/html/data/
```
## 克隆
```
$ git clone git@github.com:kdaye/ark-tools-web.git
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## 解决依赖
```
$ polymer install
```
## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## 运行
外网访问
```
$ polymer serve build/default --hostname 0.0.0.0
```
## Nginx
复制 `buid/default/*` 到 `/var/www/html`
