# libuv-echo-server
Simple libuv echo server

This is a modified version of the tcp-echo-server from:
https://github.com/bodokaiser/libuv-snippets

## Building

libuv was compiled on OS X for `x86_64` and included in the
repository for __my__ convenience. Thus, libuv does not need to be
compiled.

To compile the echo server simply use make:

    $ make echo-server

To run the server:

    $ ./echo-server

## Testing

The echo server can be tested using `netcat`. To test with `netcat`
execute the following:

    $ nc 0.0.0.0 3000

Everything you type followed by a return will be echoed back to you.

## License

Copyright © 2013 Bodo Kaiser <bodo.rene.kaiser@googlemail.com>
Copyright © 2016 Eddie Hillenbrand


Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
