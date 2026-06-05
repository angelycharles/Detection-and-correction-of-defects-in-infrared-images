# Detection-and-correction-of-defects-in-infrared-images
This project was conducted during a Data Challenge at INP Phelma – Grenoble. In the Jupyter notebook below, you will find a method and its variations for detecting defects in infrared images. The same core idea is explored through different implementations and operational strategies. Each approach aims to improve defect detection in order to achieve better image restoration.

The goal of the code was to be as fast as possible, in order to quickly select a set of potential defective columns and then allow more time-consuming analysis on these candidates to:
1.confirm whether they are true defects
2.precisely localize their spatial extent

This second step was unfortunately not achieved. However, in its current form, the algorithm performs well and is able to clean the images effectively. Although the data challenge is completed, further investigations could still be conducted to identify the issues encountered, analyze them, and explore potential solutions.
