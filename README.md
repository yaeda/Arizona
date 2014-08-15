# Arizona

A fork of Casper, the default theme for [Ghost](http://github.com/tryghost/ghost/).

## Feature
- 140 characters excerpt (for Japanese)
- Google Analytics

## Demo
[TAKESHI YAEDA](http://blog.kazeor.net/)

## Development

### Update from Casper
```sh
$ git remote add casper git@github.com:TryGhost/Casper.git
$ git fetch casper
$ git checkout -b casper-update
$ git merge casper/master

# fix conflicts
# commit
# test

$ git checkout master
$ git merge casper-update
$ git branch -d casper-update
```

## Copyright & License

Original Copyright (c) 2013-2014 Ghost Foundation - Released under the MIT License.
Modifications Copyright (c) 2014 Takeshi Yaeda - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
