# Enron-Data-Loading

Took a piece of code from a notebook on kaggle that loads the Enron Email Dataset and optimized it. 
Using multiprocessing library to be able to run code on multiple cores,
<br> and thus achieving 2mins55.14seconds vs 4mins9.27seconds on my machine.
The code uses multiprocessing pool class with imap and map, imap was used for it's less memory intesive.
Also there is a method that can be used with a with block so you can enclose any code to measure it's perfomance easily.
<br> ( kaggle notebook https://www.kaggle.com/code/zichen/explore-enron/notebook )
