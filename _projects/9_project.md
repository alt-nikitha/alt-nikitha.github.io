---
layout: page
title: Deep Traffic Analysis
description: Classification of network packets in collaboration with Defence Research and Development Organisation (DRDO)
importance: 4
category: fun
---

Most of the work in Network traffic management has been based on traditional security methods and their development. With the increase in the usage of DNS over HTTPS (DoH) and DNS over TLS as primary security protocols by browsers across the world, it is important to identify and process these packets, as well as assess their security. As part of this project, my team and I used deep learning to detect and classify DoH packets, and provide secure detection of malicious DoH as well.

We developed an algorithm that collects and disseminates DoH packets to create a new dataset through a variety of tools, one of the most important ones being – using a parser to extract the relevant packets. We then use a deep learning model to detect DoH packets in a real-world setting, which surpasses any benchmark accuracy in our specific domain. This model is an Long Short Term Memory (LSTM) network that takes in time-series data and outputs categorical scores. We also train an Support Vector Machines (SVM) model to detect malicious DoH versus benign DoH as well. 