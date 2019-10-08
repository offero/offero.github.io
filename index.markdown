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

- Node/Javascript: [telegrafjs](https://github.com/offero/telegrafjs)
- Python/Twisted: [txtelgraf](https://github.com/offero/txtelegraf)
- Golang: [go-telegraf](https://github.com/offero/go-telegraf)

### offero.tech

I am using this site to prototype NextJS, React, Material-UI, and deployment
using Zeit now.sh.

Project here: [offero.tech](https://github.com/offero/offero.tech)

### Diffusion of Innovations Simulation

This project was completed while attending George Mason University
and accomplishing a Graduate Certificate in Computational
Social Science. The project aimed to reproduce the results of
simulations performed by researchers on the spread of information
through social networks.

Project here: [DISim](https://github.com/offero/diffusionsi://github.com/offero/diffusionsim)

I hosted it originally on SourceForge and the full documentation is still
hosted there [DISim Docs](http://diffusionsim.sourceforge.net/doc/)

### Product Match

This project is an example web scraper and NLP classifier using BeautifulSoup and NLTK.
It's an example of how to collect data via web scraping and use it to produce a classifier
that can predict the category for a given text description.

It's a good example of how to do this kind of stuff with Python.

Project here: [Product Match](https://github.com/offero/productmatch)

### Algorithms

I also like to improve and test my skills on algorithm problems and I keep my
solutions to problems in a few repositories on github for reference.

- [Algorithm Playground](https://github.com/offero/algs)
- [HackerRank Algorithms](https://github.com/offero/hackerrank)
