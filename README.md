# autostart [![Build Status](https://travis-ci.org/julianduque/node-autostart.png)](https://travis-ci.org/julianduque/node-autostart)

Create autostart scripts for your applications!

## Install

```
$ npm install -g autostart
```

## Commands

### service

```
$ autostart service --name nodeapp --platform sunos --start "node app.js"
```

### command

```
$ autostart command --platform sunos --exec "forever start /opt/apps/server.js"
```

## Supported Platforms
* SunOS   - Command: `ok`       - Service: `ok`
* Linux   - Command: `pending`  - Service: `pending`
* Darwin  - Command: `peding`   - Service: `pending`
* Win32   - Command: `pending`  - Service: `pending`

## License

#### The MIT License (MIT)
Copyright (c) 2013 Julián Duque

Permission is hereby granted, free of charge, to any person obtaining a copy of 
this software and associated documentation files (the "Software"), to deal in 
the Software without restriction, including without limitation the rights to use, 
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the 
Software, and to permit persons to whom the Software is furnished to do so, subject 
to the following conditions:

The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS 
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR 
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER 
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION 
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

