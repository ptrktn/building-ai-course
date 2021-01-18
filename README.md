<!-- % -*- coding: utf-8 -*- -->

# Food Classifier

Final project for the Building AI course.

## Summary

<!--

Describe briefly in 2-3 sentences what your project is about. About
250 characters is a nice length!

-->

Cooking is an essential part of our lives and new, healthier, dishes
can be created by intelligent use of ingredients.  The objective of
this project is to classify foods based on their consitituents and
macronutrients. The classified data can then be utilised by another AI
systems to generate recommendations and new recipies.


## Background

<!-- 

Which problems does your idea solve? How common or frequent is this
problem? What is your personal motivation? Why is this topic important
or interesting?

Cooking can be likened to an art assisted by science.

-->

Currently the number of recorded recipies pales in comparision to that
of all potential recipies and the combination of ingredients to create
delicious dishes can be perceived as illogical or outright
surprising. For example, blue cheese with gingersnap cookies, ice
cream with balsamic vinegar of Modena and pineapple on pizza.
Categorisation based on constituents that give foods their flavour,
color, taste, texture and aroma creates a scientic base to create
derivative recipies and explore novel food combinations.

## How is it used?

<!--

Describe the process of using the solution. In what kind situations is
the solution needed (environment, time, etc.)? Who are the users, what
kinds of needs should be taken into account?

-->

Several uses of the categorised data can be envisioned.

* Creation of derivative recipes by substituting ingredients by
  their alternatives with similar characteristics.
* Modifying recipies based on dietary restrictions.
* Modifying recipies with seasonal produce.
* Creation of novel recipies.

## Data sources and AI methods

<!--

Where does your data come from? Do you collect it yourself or do you
use data collected by someone else?

-->

The most promising source is [FooDB](https://foodb.ca) - the world’s
largest and most comprehensive resource on food constituents,
chemistry and biology. The data is free for non-commercial use.

Creation of model for the categorisation can be addressed after
understanding of the data and model features has been
completed. Software package scikit-learn will be utilised in the
categorisation.

## Challenges

<!--

What does your project _not_ solve? Which limitations and ethical
considerations should be taken into account when deploying a solution
like this?

-->

Defining the model features will be challenging
and the physiology of taste is extremely complex.


## What next?

<!--

How could your project grow and become something even more? What kind
of skills, what kind of assistance would you need to move on?

-->

Explore the data and utilise PCA (Principal Componen Analysis) to gain
understanding how to proceed in creating the features for the
categorisation.


## Acknowledgments

Thanks to University of Helsinki and Reactor for excellent educational
material and guidance.


## References

* This, H. Molecular gastronomy: exploring the science of flavor
  (Columbia University Press, 2005).

* FooDB - https://foodb.ca

* Chun-Yuen Teng, Yu-Ru Lin, and Lada A. Adamic. 2012. Recipe
  recommendation using ingredient networks. In Proceedings of the 4th
  Annual ACM Web Science Conference (WebSci '12). Association for
  Computing Machinery, New York, NY, USA, 298–307.
  DOI https://doi.org/10.1145/2380718.2380757

* Ahn, YY., Ahnert, S., Bagrow, J. et al. Flavor network and the
  principles of food pairing. Sci Rep 1, 196 (2011).
  DOI https://doi.org/10.1038/srep00196

* Pedregosa, F. et al. Scikit-learn: Machine Learning in Python. JMLR
  12, pp. 2825-2830, 2011.
  
