---
permalink: /
title: "Profile"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**[Zack W. Almquist](https://soc.washington.edu/people/zack-almquist)** is an Associate Professor in the Department of [Sociology](https://soc.washington.edu/), an Adjunct Associate Professor in the Department of [Statistics](https://stat.uw.edu/), and a Senior Data Science Fellow in the [eScience Institute](https://escience.washington.edu/) at the [University of Washington](https://www.washington.edu/). Before coming to UW in 2020, Prof. Almquist held a Research Scientist position at [Facebook, Inc.](http://www.facebook.com) and was an Assistant Professor of [Sociology](http://www.soc.umn.edu/ Sociology) and [Statistics](http://www.stat.umn.edu/) at the [University of Minnesota](http://www.umn.edu/). He has held visiting scholar positions at [Stanford University](https://www.stanford.edu/) and the [University of Washington](https://www.washington.edu/). Dr. Almquist received his PhD from the Department of [Sociology](https://www.sociology.uci.edu/) at the [University of California, Irvine](https://uci.edu/), where he also received MAs in Sociology and Demography. He also holds an MS in Statistics from [Northwestern University](https://www.northwestern.edu/) and a BS in Mathematics from the [University of Oregon](https://www.uoregon.edu/).

Prof Almquist is a recipient of the American Sociological Association's (ASA) Section on [Methodology's](https://www.asanet.org/asa-communities/sections/methodology) [Leo Goodman Award](https://www.asanet.org/communities-sections/sections/current-sections/methodology/methodology-award-recipient-history) and the ASA’s Section on [Mathematical Sociology's](http://www.asanet.org/asa-communities/sections/mathematical-sociology) [Outstanding Dissertation Award](http://www.asanet.org/sections/mathematical_past_recipients.cfm). He is a recipient of the [NSF's](https://www.nsf.gov/) [CAREER](https://beta.nsf.gov/funding/opportunities/faculty-early-career-development-program-career) Award and the [ARO's](http://www.arl.army.mil/www/default.cfm?page=29) Young Investigator Program Award. Prof Almquist’s research has been funded by the [NSF](http://www.nsf.gov/ ), [NIH](https://www.nichd.nih.gov/), [ARO](http://www.arl.army.mil/www/default.cfm?page=29), [University of Minnesota](http://www.umn.edu/), and the [University of Washington](https://www.washington.edu/). He was elected vice chairperson (chair-elect) of the [American Public Health Association's Caucus on Homelessness](https://www.apha.org/apha-communities/caucuses/caucus-on-homelessness) (starting Fall 2024) and elected and served as the Secretary-Treasurer (<i>elected position</i>) of [ASA's Section on Mathematical Sociology](http://www.asanet.org/asa-communities/sections/mathematical-sociology) from 2018-2021. He is currently the Editor-in-Chief of the [Journal of Mathematical Sociology](https://www.tandfonline.com/journals/gmas20). He also served or serves on the Editorial Boards for the journals [*Social Networks*](https://www.journals.elsevier.com/social-networks/), [*Sociological Perspectives*](https://journals.sagepub.com/home/spx), [*Population and Environment*](https://www.springer.com/journal/11111/), and  [*Sociological Methodology*](http://journals.sagepub.com/home/smx).

Prof Almquist’s research centers on developing and applying mathematical, computational, and statistical methodology to the problems and theory of social networks, demography, education, homelessness, and environmental action and governance. His current research program is focused on understanding crucial issues around housing and homelessness, environmental action and governance, and social network methods. His research has been published in highly regarded peer-reviewed journals such as the <i>Proceedings of the National Academy of Sciences</i>, <i>American Journal of Epidemiology</i>, <i>Journal of Computational and Graphical Statistics</i>, <i>Sociological Methods & Research</i>, <i>Sociological Methodology</i>, <i>Population Space and Place<i>, <i>Mathematical Population Studies</i>, <i>American Journal of Human Biology</i> and <i>Political Analysis</i>.

------

 Working Groups
======

* [Homelessness Research Working Group](https://ssdalab.github.io/kcpehworkinggroup/)
    + Meets Fridays from 10-11:00 in Savery Hall Room 245 


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
