---
permalink: /
title: "Research page of Dr Robin Corey"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the personal web page of Dr Robin Corey, a computational biophysicist interested in membrane proteins and how they are affected by their lipid environment. 

Undergraduate and postgraduate research
======
I got my undergraduate BSc in Biochemistry from the [University of York](https://www.york.ac.uk/). Here I worked for two terms in the lab of [Professor Neil C Bruce](https://www.york.ac.uk/biology/research/plant-biology/neil-c-bruce) on a cytochrome P450 which breaks down the explosive RDX.

I then carried out a MSc and PhD at the [University of Bristol](https://bristol.ac.uk/biochemistry/), working in the lab of [Professor Ian Collinson](https://www.bristol.ac.uk/people/person/Ian-Collinson-0cde2e1b-6fb7-4a0a-9ae8-34ee83d80d6a/). Here, I used a range of experimental techniques (including functional assays, FRET, X-ray crystallography, SEC-MALS, and non-natural amino acid substitution) as well as computational methods (including molecular dynamics, molecular modelling, and free energy calculations) to determine the mechanism of protein-secretion in bacteria via SecYEG.A, a key component of bacterial virulence and a promising target for antibiotics. We have now published a series of papers on this topic, combining both experimental and computationl analyses. This includes work on how ATP binding and hydrolysis drives protein secretion via a Brownian ratchet (published in [four](https://elifesciences.org/articles/15598), [separate](https://elifesciences.org/articles/41803), [_eLife_](https://elifesciences.org/articles/35112), [papers](https://elifesciences.org/articles/47402) ), and how the membrane proton motive force also contributes to this (manuscript in preparation). In addition, we have studied how the SecY translocon is "unlocked" by pre-protein (published in [_Structure_](https://www.sciencedirect.com/science/article/pii/S0969212616000460), and how the phospholipid cardiolipin bindings and functionally-modulates SecYEG (published in [_PNAS_](https://www.pnas.org/content/115/31/7967.short)).

SecYEG.A bound to cardiolipin
![SecYEG.A bound to cardiolipin](/images/Sec_CL.png)


Postodoctoral research
======
I have worked at the [University of Oxford](https://www.bioch.ox.ac.uk/) as a postdoc in the labs of [Professor Mark Sansom](https://www.bioch.ox.ac.uk/research/sansom) and [Dr Phillip Stansfeld](https://warwick.ac.uk/fac/sci/lifesci/people/pstansfeld/) since 2018. See the Stansfeld Research website [here](https://stansfeldresearchgroup.wordpress.com/).

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
