# gopher-lua-libs
[![GoDoc](https://godoc.org/github.com/vadv/gopher-lua-libs?status.svg)](https://godoc.org/github.com/vadv/gopher-lua-libs)
[![Travis](https://travis-ci.org/vadv/gopher-lua-libs.svg)](https://travis-ci.org/vadv/gopher-lua-libs)

Package contains is a libs for [gopher-lua](https://github.com/yuin/gopher-lua).

## License

Development version, available on github, released under BSD 3-clause.

## Installation

```
go get github.com/vadv/gopher-lua-libs
```

## Index

* [cert_util](/cert_util) monitoring ssl certs
* [chef](/chef) chef client api
* [cmd](/cmd) cmd port
* [crypto](/crypto) calculate md5, sha256 hash for string
* [db](/db) access to databases
* [filepath](/filepath) path.filepath port
* [goos](/goos) os port
* [http](/http) http.client && http.server
* [humanize](/humanize) humanize [github.com/dustin/go-humanize](https://github.com/dustin/go-humanize) port
* [inspect](/inspect) pretty print [github.com/kikito/inspect.lua](https://github.com/kikito/inspect.lua)
* [ioutil](/ioutil) io/ioutil port
* [json](/json) json implementation
* [plugin](/plugin) run lua code in lua code
* [regexp](/regexp) regexp port
* [runtime](/runtime) runtime port
* [storage](/storage) package for store persist data and share values between lua states
* [strings](/strings) strings port (utf supported)
* [tac](/tac) tac line-by-line scanner (from end of file to up)
* [tcp](/tcp) raw tcp client lib
* [telegram](/telegram) telegram bot
* [template](/template) template engines
* [time](/time) time port
* [xmlpath](/xmlpath) [gopkg.in/xmlpath.v2](https://gopkg.in/xmlpath.v2) port
* [yaml](/yaml) [gopkg.in/yaml.v2](https://gopkg.in/yaml.v2) port
* [zabbix](/zabbix) zabbix bot

## Standalone interpreter with listed libs

```
go get github.com/vadv/gopher-lua-libs/cmd/glua-libs
```
