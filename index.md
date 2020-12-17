## Welcome to Adaptateur's Data Story

This work explore the general graph properties of three websites, [Epinions](www.epinions.com), [Slashdot](https://slashdot.org/) and [wikipedia](https://en.wikipedia.org/wiki/Main_Page)

We propose to study the popularity of the users in social media and their like/dislike behavior. For this purpose, we set to main axes, first we focus on the received votes, then we look at the voters behavior.

The github repo of our project is available [here](https://github.com/epfl-ada/ada-2020-project-milestone-p3-p3_adaptateur).


## Popularity & fame : How a user is considered by other users ?

Let's start with some definitions !
`Fame`: the number of inner edges a user get positive and negative links.
`Popularity`: the proportion ratio of positive inner links a user received over the total inner edges 

Now that we have this definitions, we can ask ourselves how fame and popularity are distributed over the three aforementioned websites.

[//]: # (Insert graphix)

Note that Wikipedia not having the same voting process than the two other website is here visible in the distributions.  For Slashdot and Epinions, we observe a power law distribution while for Wikipedia the distribution seems to follow a linear trend. 

Indeed, Shashdot and Epinions work as classical social media, where people who would like to be famous follow and vote for famous people. This phenomenon correspond to the social media theorie in data science. However Wikipedia voting system is intern to administrator network. The network is structured differently because administrators vote in a more rationnal way.

[//]: # (Expliquer comment fonctionne le principe de vote sur les sites -> Epinions/Slashdot vs Wikipedia -> Intro ?)

[//]: # (Regarder comment faire des séparation entre les "zones")
-----------------

Are popularity and fame linked ? Or could one be super famous but hated ? Like a despotic tyrant ?

[//]: # (insert graphix)






### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Floumzi/ADataStory/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
