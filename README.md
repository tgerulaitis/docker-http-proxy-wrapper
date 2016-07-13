# Docker HTTP proxy wrapper script

docker-http-proxy is a wrapper script to make it easy to start and manage the meanbee/nginx-proxy docker container. You can read more about the container [here](https://github.com/meanbee/docker-nginx-proxy) and [here](https://github.com/jwilder/nginx-proxy).

## Installation

    curl https://raw.githubusercontent.com/tgerulaitis/docker-http-proxy-wrapper/master/docker-http-proxy -k -o docker-nginx-proxy
    chmod +x docker-nginx-proxy

## Usage

    ./docker-nginx-proxy <command>

    Available commands:
        name     Print out the name of the HTTP proxy container.
        status   Print out the status of the HTTP proxy container.
        start    Start the HTTP proxy container, creating it if necessary.
        stop     Stop the HTTP proxy container.
        rm       Destroy a stopped HTTP proxy container, including its volumes.

## License

Copyright (c) 2016 Tomas Gerulaitis <t.gerulaitis@gmail.com>

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
