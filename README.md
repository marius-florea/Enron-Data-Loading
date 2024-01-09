# Enron Data Loading Optimization

Took a piece of code from a notebook on kaggle that loads the Enron Email Dataset and optimized it. 
<br> Using multiprocessing library to be able to run code on multiple cores, and thus achieving 2mins55.14seconds vs 4mins9.27seconds on my machine.
<br> The code uses multiprocessing pool class with imap and map, imap was used for it's less memory intesive.
<br> Also there is a method that can be used with a 'with block' so you can enclose any code to measure it's perfomance easily.
<br> For testing you will need the email dataset, that can be found on kaggle, it is not posted here since it is a large file(1.4GB).
<br> ( kaggle notebook https://www.kaggle.com/code/zichen/explore-enron/notebook )

