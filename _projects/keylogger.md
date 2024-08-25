---
layout: page
title: keylogger
description: a Python-based keylogger that monitors specific applications and captures keystrokes
img: assets/img/keylogger.jpg
importance: 1
redirect: https://github.com/mahir-b0/keylogger
category: work
related_publications: true
---

This project is created **strictly** for educational purposes and as a proof of concept. Unauthorised use of keyloggers is illegal and unethical.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/keylogger1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Overview

This project is a sophisticated keylogger script designed to monitor specific applications and capture various types of data only when those applications are active. It is built in Python and integrates several libraries to provide comprehensive data collection, including keystrokes, clipboard content, system information, and screenshots.

## Rationale

I was researching some projects I might be able to work on coding in Python, and I came across a simple keylogger project which, in 19 lines of code, wrote a program which can efficiently capture the keystrokes a user makes while the program is running. I thought, well if I was a threat actor, I wouldn't want to capture *EVERYTHING* a user is typing (theoretically), but rather what was relevant. And speaking of relevance, I realised that there was a LOT more you could capture while a program was running in the background. So I did some research and came across various libraries in python which were capable of retrieving the user's IP address, screenshotting, and more. So I extended upon the initial design to incorporate some of these features, as well as only activating while the user is running 'vulnerable' programs like Chrome, because, again framing myself in an attacker's mindset, I'd only really be interested in things like passwords, usernames and other sources of sensitive data.


