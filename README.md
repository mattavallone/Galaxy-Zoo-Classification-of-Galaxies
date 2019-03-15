# Galaxy Zoo: The Galaxy Challenge

This Jupyter Notebook was created as a HW assignment for CS9223 Deep Learning course at NYU. It is based off of the original Kaggle Competition, Galaxy Zoo, which took place in 2014.

The competition prompt:

Understanding how and why we are here is one of the fundamental questions for the human race. Part of the answer to this question lies in the origins of galaxies, such as our own Milky Way. Yet questions remain about how the Milky Way (or any of the other ~100 billion galaxies in our Universe) was formed and has evolved. Galaxies come in all shapes, sizes and colors: from beautiful spirals to huge ellipticals. Understanding the distribution, location and types of galaxies as a function of shape, size, and color are critical pieces for solving this puzzle.

With each passing day telescopes around and above the Earth capture more and more images of distant galaxies. As better and bigger telescopes continue to collect these images, the datasets begin to explode in size. In order to better understand how the different shapes (or morphologies) of galaxies relate to the physics that create them, such images need to be sorted and classified. Kaggle has teamed up with Galaxy Zoo and Winton Capital to produce the Galaxy Challenge, where participants will help classify galaxies into categories.

Galaxies in this set have already been classified once through the help of hundreds of thousands of volunteers, who collectively classified the shapes of these images by eye in a successful citizen science crowdsourcing project. However, this approach becomes less feasible as data sets grow to contain of hundreds of millions (or even billions) of galaxies. That's where you come in.

This competition asks you to analyze the JPG images of galaxies to find automated metrics that reproduce the probability distributions derived from human classifications. For each galaxy, determine the probability that it belongs in a particular class. Can you write an algorithm that behaves as well as the crowd does?

Further info about the Kaggle challenge can be found here: https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge

_______________________________________________________________________________________________________________________________

A CNN was implemented using Keras and achieved a test RMS error of 0.06133, which easily surpasses the winning error for the competition.
This repository includes the notebook and the test output submissions.
