# TestTerminal

Proof of concept terminal.

This is a small component of a much larger system including authentication, access control and security - do not use it.

## Getting

```
go get github.com/freman/goterm
```

## Running

Not included is https://github.com/sourcelair/xterm.js

```
cd src/github.com/freman/goterm/assets
git clone https://github.com/sourcelair/xterm.js
$GOPATH/bin/goterm -assets `pwd`
```