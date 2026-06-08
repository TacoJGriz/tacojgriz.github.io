---
title: "NLP on Real Time Systems"
excerpt: "<img src='/images/nlpthumbnail.png'>"
collection: portfolio
---

In my real-time/embedded systems course, I conducted an intriguing reaserch project on natural language processing (NLP) in real-time systems. My goal was to compare various NLP models, and deploy different strategies to make them as deterministic as possible. I compared the performance of a LSTM model, a GRU model, and a double GRU early exit model. After building and training these models in Python, I ran my models in C++ via ONNX with various optimizations to decrease runtime and jitter. Initially, I was worried to come up with and tackle this project, as I had no prior experience with research projects as such. However, I ended up having a lot of fun working on this project, and seeing this project through to the end was very rewarding. My hope is that this research can be used to help improve accesibility in time-sensitive systems.
For those interested in exploring this topic further, my research report is located [here](/files/GrizzleJacksonNLP.pdf), and the code I used can be found  [here](https://github.com/TacoJGriz/NLP-realtime)
