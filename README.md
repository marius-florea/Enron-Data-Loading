# Enron-Data-Loading

Took the code from a notebook on kaggle that loads the Enron Email Dataset and optimized it. 
Using multiprocessing library to be able to run code on multiple cores,
and thus achieving 2mins nd55.14seconds vs x on my machine.
The code uses multiprocessing pool class with imap and map, imap was used for it's less memory intesive.
Also there is a method that can be used with a with block so you can enclose any code to measure it's perfomance easily.
