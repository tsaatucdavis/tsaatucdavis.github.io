---
layout: post
title: "Gaussian Process (GP): A Brief Introduction"
description: "What is GP? Why is it useful?"
comments: true
---

This post aims to provide a simple introduction to Gaussian Process (GP) for regression purposes.

It's that time of the year when a major vision conference [releases the papers to the public](http://openaccess.thecvf.com/CVPR2018.py), so it's time to check how deep learning is doing in their titles.<br>
<br>
At ICCV 2017, we realized that [GANs were growing strong]({{ site.url }}/gans-et-al-growing-strong/), and before we did a set [of]({{ site.url }}/dl-lstm-gan-evolution) [posts]({{ site.url }}/deep-learning-scraping/) of [the]({{ site.url }}/deep-learning-plateau/) [deep learning]({{ site.url }}/deep-learning-takes-over-again/) [saga]({{ site.url }}/deep-learning-evolution/).<br>
<br>
Let's update the plots to CVPR 2018, as always, using the XKCD style, as described in this [blog post]({{ site.url }}/xkcd-deep-learning/), but this time putting all trends together:
<br />
<img align="middle" width="500" src="{{ site.url }}/images/deep_vs_gan_evolution.png" alt="...">
<br />
<br />

So, general deep-learning keywords are getting out of fashion (we take them for granted), but GANs are no longer such a minority (8\%!). LSTM, on the other hand, cannot keep up. Will GANs catch up with general deep learning?<br />
<br />
Are GANs the new Deep?


Here’s our first event for this quarter: Fall Welcome! Come chat with us and enjoy a cup of Turkish tea. Thank you all for coming and joining us today in our first meeting :) We are looking forward to seeing you again.<br>

Bu dönemin ilk eventiyle karşınızdayız: Tanışma Toplantısı. Gelin beraber sohbet edip demleme çayın keyfini çıkaralım. Ilk buluşmamızda bizlere eşlik eden herkese teşekkür ederiz :) En yakın zamanda görüşmek üzere.<br>

<img align="middle" width="500" src="{{ site.url }}/images/tanisma-toplantisi.png" alt="...">
