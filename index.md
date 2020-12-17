## Welcome to Adaptateur's Data Story

This work explore the general graph properties of three websites, [Epinions](https://shopping.com/), [Slashdot](https://slashdot.org/) and [Wikipedia](https://en.wikipedia.org/wiki/Main_Page).

We propose to study the popularity of the users in social media and their like/dislike behavior. For this purpose, we set to main axes, first we focus on the received votes, then we look at the voters behavior.

The github repo of our project is available [here](https://github.com/epfl-ada/ada-2020-project-milestone-p3-p3_adaptateur).

-----------------

## Popularity & fame : How a user is considered by other users ?

Let's start with some definitions ! \\
`Fame`: the number of inner edges a user get positive and negative links. \\
`Popularity`: the ratio of positive inner links a user received over the total inner edges.


### Distribution

Now that we have this definitions, we can ask ourselves how fame and popularity are distributed over the three aforementioned websites.

[//]: # (Insert graphix)

Note that Wikipedia not having the same voting process than the two other website is here visible in the distributions.  For Slashdot and Epinions, we observe a power law distribution while for Wikipedia the distribution seems to follow a linear trend. 

Indeed, Shashdot and Epinions work as classical social media, where people who would like to be famous follow and vote for famous people. This phenomenon correspond to the social media theory in data science. However Wikipedia voting system is intern to administrator network. The network is structured differently because administrators vote in a more rationnal way.

[//]: # (Expliquer comment fonctionne le principe de vote sur les sites -> Epinions/Slashdot vs Wikipedia -> Intro ?)

-----------------

### Are popularity and fame linked ?
Or could one be super famous but hated ? Like a despotic tyrant ?

[//]: # (insert graphix)

As before, we denote a difference between Wikipedia, where most famous users are not necessarly the one with the highest popularity, and the two other websites where . Hence there is no despotic tyrant... or at least they are not using one of these websites !

-----------------

### Evolution over time
How did the overall popularity within a website evolved ? \\
Unfortunately, Slashdot dataset did not record the time of the votes so we based our time analysis only on Wikipedia and Epinions.

[//]: # (insert graphix)


Je sais pas quoi dire je suis pas sûre de ce graph -> average plutot ?


---------------

### Evolution of the most famous / popular ursers.


---------------

## Haters & lovers : How users interact with each others ?

Once again, some useful definitions : \\
`activity`: the total review a user performed
`hater/lover`: the proportion ratio of positive outer links a user send over the total outer edges


### Markdown
[Link](url) and ![Image](src)
