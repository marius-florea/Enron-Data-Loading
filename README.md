# Enron-Data-Loading

Took a piece of code from a notebook on kaggle that loads the Enron Email Dataset and optimized it. 
Using multiprocessing library to be able to run code on multiple cores,
and thus achieving 2mins and55.14seconds vs 4mins and9.27seconds on my machine.
The code uses multiprocessing pool class with imap and map, imap was used for it's less memory intesive.
Also there is a method that can be used with a with block so you can enclose any code to measure it's perfomance easily.
( kaggle notebook https://www.kaggle.com/code/zichen/explore-enron/notebook )
