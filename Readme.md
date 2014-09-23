
# grid-print

Grid for printing

## Installation

Install with [component(1)](http://component.io) (version lower than 1.0):

    $ component install chameleonui/grid-print

## API

### Use flags

You can disable or enable grid features through use-flags:

```
// Debug is disabled by default
use-print-grid-tiles = true|true;
```

### Variables
```
// Globals, inherit from other installed grid, so you usually don't need to define these again
grid-columns-count ?= 12;
grid-row-width ?= 64em;
grid-row-max-width ?= grid-row-width;
grid-gutter-width ?= 1.875em;
grid-column-class ?= "column";
grid-tiles-columns-from ?= 1;
grid-tiles-columns-to ?= 12;

// Custom print variables
print-grid-span-class = "print";
print-grid-offset-class = "print-offset";
print-grid-pull-class = "print-pull";
print-grid-push-class = "print-push";
print-grid-centered-class = "print-centered";
print-grid-uncentered-class = "print-uncentered";
print-grid-tiles-class = "print-tiles";
```

### Init

```
grid-print();
```

## Author(s)

[Edgedesign s.r.o.](http://www.edgedesing.cz) – [Daniel Sitek](https://github.com/danielsitek)

## License

The MIT License (MIT)

Copyright © 2013 Edgedesign s.r.o.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.