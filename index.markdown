---
layout: page
title: "Offero's Well"
permalink: /
---

# Here you will find my open source code and tech blog.

## Code

### Telegraf Clients

I have used Influx DB and the TICK stack in my work. It's a great
toolset to measure, monitor, and alert on near real time events.
Influx DB is a time series database.

It's important to have a simple, reliable, and unobtrusive way of
emitting metrics to Influx DB. Telegraf is a tool written to collect
metrics and send them to Influx. If you want to log and graph custom
application specific measurements, then your program has to emit
metrics to Influx. My preferred way of doing so is by running an
instance of telegraf along side my application and letting it collect
and emit those events to Influx for me. That means that you have to
emit the measurements to telegraf instead. There is a text line
specification for Influx measurements. In order to allow my applications
to easily emit measurements to telegraf, I wrote a few libraries in
languages I frequently use.

- Node/Javascript: [telegrafjs](https://github.com/offero/telegrafjs){:target="_blank"}
- Python/Twisted: [txtelgraf](https://github.com/offero/txtelegraf){:target="_blank"}
- Golang: [go-telegraf](https://github.com/offero/go-telegraf){:target="_blank"}


### Bamboo, a Redis-backed Job Queuing System

At Wanderu, I built and open-sourced a job queuing system built on top of
Redis. The system itself is a reliable distributed redis-backed job queuing
system with ack/fail semantics and support for multiple languages.

There were a bunch of reasons to build a custom solution with some
required properties for our use cases. Existing Python and Node solutions
were missing properties that we needed, so I built and open-sourced this.

- Redis LUA scripts: [lua-scripts](https://github.com/Wanderu/bamboo-scripts){:target="_blank"}
- Python Client: [wanderu.bamboo](https://github.com/Wanderu/wanderu.bamboo){:target="_blank"}
- Javascript Client: [jsbamboo](https://github.com/Wanderu/jsbamboo){:target="_blank"}
- Go Client: [go-bamboo](https://github.com/Wanderu/go-bamboo){:target="_blank"}


### offero.tech

I am using this site to prototype NextJS, React, Material-UI, and deployment
using Zeit now.sh.

Project here: [offero.tech](https://github.com/offero/offero.tech){:target="_blank"}

### Diffusion of Innovations Simulation

This project was completed while attending George Mason University
and accomplishing a Graduate Certificate in Computational
Social Science. The project aimed to reproduce the results of
simulations performed by researchers on the spread of information
through social networks.

Project here: [DISim](https://github.com/offero/diffusionsi://github.com/offero/diffusionsim){:target="_blank"}

I hosted it originally on SourceForge and the full documentation is still
hosted there [DISim Docs](http://diffusionsim.sourceforge.net/doc/){:target="_blank"}

### Product Match

This project is an example web scraper and NLP classifier using BeautifulSoup and NLTK.
It's an example of how to collect data via web scraping and use it to produce a classifier
that can predict the category for a given text description.

It's a good example of how to do this kind of stuff with Python.

Project here: [Product Match](https://github.com/offero/productmatch){:target="_blank"}

### Algorithms

I also like to improve and test my skills on algorithm problems and I keep my
solutions to problems in a few repositories on github for reference. *ALL* code
is my own.

- [Algorithm Playground](https://github.com/offero/algs){:target="_blank"}
- [HackerRank Algorithms](https://github.com/offero/hackerrank){:target="_blank"}
