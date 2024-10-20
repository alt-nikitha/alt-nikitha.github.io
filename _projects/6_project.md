---
layout: page
title: Detecting COVID-19 Onset from Wearables
description: Maybe your fitness trackers can tell you if you are infected with COVID-19
img: assets/img/heart.jpg
importance: 4
category: fun
---

While health experts cannot constantly monitor a person’s physiological indicators, a wearable can do the job. It can track a person’s heart rate, sleep patterns, body temperature, and several other parameters over time, and identify any deviations from normal. This can help predict the onset of health issues before the appearance of visible symptoms, ensuring timely treatment. It can also help experts study the effects produced over time and better understand the course of illnesses. In this <a href="https://github.com/alt-nikitha/Using-LSTMs-and-LIME-to-understand-Covid-19-HRV-measurements"> project </a>, I used data from wearable sensors is used to train an LSTM model for the classification of heart rate variability over time. This model demonstrates 87% test accuracy. Also, the model is interpreted to analyse which measures of heart rate variability could best explain the heart rate changes due to COVID-19 (see below).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/covidinterpret.jpg" title="interpret-lime" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example of factors that influence the model's detection of COVID-19 for a certain sample of observations
</div>