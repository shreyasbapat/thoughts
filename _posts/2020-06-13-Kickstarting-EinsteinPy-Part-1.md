---
layout: post
title: "Kickstarting EinsteinPy: Part 1"
tags:
- einsteinpy
- python
---

I was sitting in a guest lecture at my University [IIT Mandi](https://iitmandi.ac.in) about the General Theory of Relativity. Usually, whenever I go to these lectures, I am accompanied by my good friend [Bhavya Bhatt](https://github.com/spino17). We both stuck at a point where we're not able to visualize what exactly is going on with the Black Hole. I asked Bhavya, "Is there a way to possibly simulate this stuff?". He replied, "Yes, there is. It's called Einstein Toolkit. I've heard that it is difficult to install. But I will still try!". Few days passed by and we met again in the mess. I asked what the progress was, and Bhavya in a sad tone told me that he tried but this software was based on some weird Cactus Thorne Framework.

A month passed and we had nothing. Then we gave up. I mentioned in the last meeting, about creating a Python Package which can make this easy. And then we saw a long radio silence.

After about 3 months, we were again in the same place, getting bored. And definitely had nothing good to do. So we decided that we will start writing the Python Package. We named it [EinsteinPy](https://einsteinpy.org). It was 30 January 2019 when we made the first commit to the repository.

Then it never stopped. Now we have around 200 Stars, which is a big thing for a Scientific Python Package with so focused use case.

![EinsteinPy Logo](https://blog.einsteinpy.org/img/logo.png)

We had accepted a student in Google Summer of Code 2020 and ESA Summer of Code in Space 2019.

EinsteinPy is an open-source pure Python package dedicated to problems arising in General Relativity and gravitational physics, such as geodesics plotting for Schwarzschild, Kerr and Kerr Newman space-time model, calculation of Schwarzschild radius, calculation of Event Horizon and Ergosphere for Kerr space-time. Symbolic Manipulations of various tensors like Metric, Riemann, Ricci, Ricci Scalar, Weyl, Schouten, Stress-Energy-Momentum, Einstein, and Christoffel Symbols is also possible using the library. EinsteinPy also features Hypersurface Embedding of Schwarzschild space-time, which will soon lead to the modelling of Gravitational Lensing! It is released under the MIT license.

The code can be seen here: [https://github.com/einsteinpy/einsteinpy](https://github.com/einsteinpy/einsteinpy)

The documentation can be seen here: [https://docs.einsteinpy.org](https://docs.einsteinpy.org)
