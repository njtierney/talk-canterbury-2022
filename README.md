# Extendable projection of social contact matrices

# Abstract

Contact matrices describe the degree of face-to-face contact between individuals of given age groups. These matrices are commonly used to model how diseases such as COVID-19 spread in a population through social contact. Contact matrices are produced from empirical data resulting from a contact survey, which requires individuals to diary the amount and manner of contact a person has in a day. However, these surveys are highly time-consuming and expensive to run, meaning that there exists only a handful of these empirical datasets globally. 

There are existing statistical methodologies to project empirical contact matrices to new countries - e.g. those produce by Prem et al. Existing work provides these synthetic contact matrices for a fixed set of countries, at specific points in time. Infectious disease modellers therefore face a problem when developing models for countries not considered in these analyses, or for subpopulations within those countries. We need software to implement these methods so they can be flexibly reused on different populations.

We have developed methods for creating synthetic contact matrices that uses existing contact surveys but can be used to create synthetic contact matrices  for any new age population structure. These methods are available in the R package {conmat}. {conmat} contains a suite of tools for using these synthetic matrices in other epidemiology concepts, such as generating a next generation matrix (incorporating age-varying transmission parameters), and adjusting transmission according to vaccination rates. 

In this talk, I demonstrate the use of the {conmat} package, showcasing how it can be used in epidemiological analyses. I will also discuss the process of creating the software and the user interface.

# Slide available [here](https://njtierney.github.io/talk-canterbury-2022/)

# Bio

Dr. Nicholas Tierney (PhD. Statistics, BPsySci (Honours)) is a research software engineer with [Nick Golding](https://www.telethonkids.org.au/contact-us/our-people/g/nick-golding/) at the [Telethon Kids Institute](https://www.telethonkids.org.au/), in Perth, Western Australia. He works on improving and maintaining the [greta](https://greta-stats.org/) R package for statistical modelling, and implementing workflows to automate analysis on diseases like COVID19 and malaria. He was previously (2017-2020) a Research Fellow, then Lecturer in Business Analytics and Statistics at Monash University, working with Professors
[Dianne Cook](http://dicook.org/) and [Rob Hyndman](https://robjhyndman.com/).

His research aims to improve data analysis
workflow, and make data analysis more accessible. Crucial to this work is producing high quality software to
accompany each research idea. Recently, Nick's work has focussed on exploring longitudinal data ([brolgar](http://brolgar.njtierney.com/)), and improving how we share data alongside research ( [ddd](https://github.com/karthik/ddd)). Other work has focussed on exploring data
with the R package [visdat](http://visdat.njtierney.com/), and on creating analysis principles and tools
to simplify working with, exploring, and modelling missing data with the
package [naniar](http://naniar.njtierney.com/). Nick has experience working with decision trees ([treezy](http://treezy.njtierney.com/)),
optimisation ([maxcovr](http://maxcovr.njtierney.com/)), Bayesian Data Analysis, and MCMC diagnostics ([mmcc](http://mmcc.njtierney.com/).

Nick is a member of the [rOpenSci](https://ropensci.org/) collective, which works to make science
open using R, has been the lead organiser for the rOpenSci ozunconf
events from 2016-2018 ([2016](https://auunconf.ropensci.org/), [2017](https://ozunconf17.ropensci.org/), [2018](https://ozunconf18.ropensci.org/)). Outside of research, Nick likes to
hike, trail run, kayak, rockclimb, make coffee, bake sourdough, (eventually) knit a hat, carve spoons, take photos, and explore new hobbies.
