# G3deon Inc Common CQL Package

![Repository banner](/assets/g3-cqlx-banner.png)

## Translations

You can view the documentation in your preferred language:

- English. (Current translation)
- Spanish. [View in Spanish](/README-ES.md).
- Portuguese (Brazil). [View in Portuguese](/README-BR.md).

## Frequently Asked Questions (FAQs)

### Why g3-cqlx?

At [G3deon Inc](https://g3deon.com), we have a distributed architecture, specifically microservices. As we don't work with a monorepo, we've realized that in many of our microservices, we've repeated a lot of code. Given this scenario, to improve the maintainability and scalability of our service, we've separated this repeated code into libraries. This is where **g3-cqlx** comes in, a library for integrating cqlx with the standards we follow at [G3deon Inc](https://g3deon.com).

### Why not use gocqlx directly?

With **g3-cqlx**, our goal is to have the most commonly used functions, but that doesn't mean you can't use [gocqlx](https://github.com/scylladb/gocqlx) directly. You can, but you can also utilize the functions of g3-cqlx if you're going to perform basic and repetitive actions.

## License

This project is licensed under the *MIT License*.

```md
MIT License

Copyright (c) 2024 G3deon, Icon.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
