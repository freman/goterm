# TestTerminal

Proof of concept terminal.

![image](https://cloud.githubusercontent.com/assets/8284169/15344054/6f3aff7a-1ce6-11e6-8e54-c2edb303f944.png)


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
