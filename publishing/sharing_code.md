# Sharing code with a scientific manuscript

Nowadays, most scientific projects include some level of computer coding: data analysis, graph production, modelling, image analysis, etc. 

It is important that this code is freely available at the time of publication (#OpenScience), for several reasons:

- better reproducibility of your study
- better valorisation of your work (others will re-use it)
- easier quality check by others (everybody make mistakes. EVERYBODY!)

Fortunately, it is really easy to share your code a the time of publication. Here is my own prefered strategy:

## 1. Prepare your code

Try to prepare your code in a way that it will be understandable by others. The more easy it is to understand, the better chance you have it will be re-used. 

That said, keep in mind that no code (or comment) is perfect! A shared losely commented code is much (much!) better than no code at all. So no pressure. If your do not think your code is good enough to be share, that is normal. Everybody feels the same. 

Share it anyway!



## 2. Share your code

- create a GitHub account ([www.github.com](www.github.com))
- create a specific repository for your study / work (such as this one: [https://github.com/guillaumelobet/Root-Image-Analysis-Pipeline-Evaluation](https://github.com/guillaumelobet/Root-Image-Analysis-Pipeline-Evaluation))
- make the repository public, for everyone to access

![](https://github.com/guillaumelobet/ressources/blob/master/imgs/github_public.png)

Congrats, your code is now freely available (and easily browsable) to others! 


## 3.  Include some data

    Thanks to Alina Zare (@ProfZare) for suggesting this section

If your code run with some data, these will be needed in order to ru it. On solution it to add a link to the full dataset, stored on an external platform such as [Zenodo](http://www.zenodo.org), [figshare](http://www.figshare.com) or [Dryad](https://datadryad.org/). An toehr solution is to include a subset of your data, enough to run your code, in the GitHub repo.  

## 4. Make it citable

Now that your code is available, you can do even better. Make it citable! See, the issue with your repo is that there are no garanties that it will stay as it is on the long run. You might update it (which is great), improve it (even better), but then the code is not the same as the one used for your original manuscript anymore (reproducibility - )... 

The solution is to create a permanent version for your code, and give it a DOI (Digital Object Identifier). You will then be able to share and cite your code in a permanent, stable way. 

To do so, GitHub can be linked to a Zenodo repository. [Zenodo](http://www.zenodo.org) is a data hosting plateform, funded by the EU and hosted at CERN. So a decent long term solution for the storage of scientific code!

You can read the exact procedure to link you GitHub repo to Zenodo here: [https://guides.github.com/activities/citable-code/](https://guides.github.com/activities/citable-code/)

## 5. All set!

Now you are all set. Your code is frelly available and easily citable, by yourself and others!




