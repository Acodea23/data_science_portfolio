~~~
title : How to handle (model) sensitivity
format: html
~~~

# How to handle (model) sensitivity
words to know: *scalable, bayesian, prior*

When learning to build statisitcal models, the moment the model "fits" the data and your assumptions are met you tend to pat yourself on the back and call it a day. But in the *wild*, models need to be [scalable](#Scalability). They need to be resistant to our [prior beliefs](#Prior-Beliefs) potentially bleeding into the model. We will consider how sensitivity relates to these topics, and how to prevent oversensitivity.

# Scalability

