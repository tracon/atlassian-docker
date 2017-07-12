# Tracon's Atlassian software setup

We run Crowd, Confluence and JIRA with some configuration particulars:

* Crowd is used to provide single sign on for Confluence and JIRA
* Confluence and JIRA are configured to perform login via [Kompassi](https://github.com/tracon/kompassi)
* All software is executed in Docker containers

This repository serves as example configuration for others who are facing similar setups. Work in progress.

## Try it out locally

    docker-compose up

## Deploy it for production

See [ansible-tracon](https://github.com/tracon/ansible-tracon).

## License

Crowd, Confluence and JIRA are covered by their respective proprietary license agreements.

All original work by Tracon hosted in this repository is covered by the following license:

    The MIT License (MIT)

    Copyright © 2013-2017 Santtu Pajukanta, Jussi Sorjonen, Miika Ojamo

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
