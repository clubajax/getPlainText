# getPlainText

## Description

Normalizes innerText across browsers

Returns a line-break'ed, properly spaced, normalized plain text
representation of multiple child nodes which can't be done via
textContent or innerText because those two methods are vastly
different, and even innerText works differently across browsers.

More info here:
[Plain Text vs textContent vs innerText](http://clubajax.org/examples/plain-text-vs-textcontent-vs-innertext/)

## Disclaimer

This is code I wrote in 2010, and in general it's not supported. However, I was
surprised to find the effort is still relevant, thanks to the kudos given by
[kangax](http://perfectionkills.com/the-poor-misunderstood-innerText/)

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>