---
permalink: /
title: About Me
description: "Jiatao Gu's website"
author_profile: true
image:
  feature: blackhole.png
redirect_from: 
  - /about/
  - /about.html
---

I am currently a research scientist at the [Facebook AI Research](https://research.fb.com/category/facebook-ai-research/) in New York City. My general research interests lie in applying deep learning approaches to natural language processing (NLP) problems. In particular, I am interested in building an efficient, effective and reliable neural machine translation (NMT) system for human languages.

I obtained my Ph.D. degree at the department of Electrical and Electronic Engineering, University of Hong Kong in 2018 and I was supervised by [Prof. Victor O.K. Li](https://www.eee.hku.hk/people/vli/). 
I spent a wonderful time visiting the [CILVR Lab](https://wp.nyu.edu/cilvr), New York University working with [Prof. Kyunghyun Cho](http://www.kyunghyuncho.me/).
Before that, I obtained my Bachelor's degree at the Electronic Engineering Department, Tsinghua University in 2014 with the guidance of [Prof. Ji Wu](https://www.tsinghua.edu.cn/publish/eeen/3784/2010/20101219135614305780920/20101219135614305780920_.html).


<!-- Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html). -->

What's New?
------
**2019-12-18**: Four [papers](/publication/understand-distillation) were accepted at **ICLR 2020**. See you in [Addis Ababa, ETHIOPIA](https://www.google.com/maps/place/Millennium+Hall/@8.9902942,38.7895542,15z/data=!4m2!3m1!1s0x0:0xbb84990929808c9a?sa=X&ved=2ahUKEwi6lZ7wmbrjAhWWFTQIHYFzAhMQ_BIwE3oECA4QCA)! <br>
**2019-11-10**: One [paper](/publication/byte-level-nmt) was accepted at **AAAI 2020**. See you in New York :) <br>
**2019-09-03**: One [paper](/publication/levenshtein-transformer) was accepted at **NeurIPS 2019**. See you in Vancouver!<br>
**2019-08-12**: One demo paper was accepted to present at **EMNLP2019**!<br>
**2019-07-24**: One paper was accepted at **TACL** and will be presented in **EMNLP2019**. See you in Hong Kong!<br>
**2019-05-14**: One paper was accepted at **ACL2019**!<br>
**2019-03-29**: Two papers was accepted at **NAACL2019 NeuralGen Workshop**. See you in Minneapolis!<br>
**2018-08-20**: I started my new position as a research scientist at Facebook AI Research (FAIR) in NYC.

<!-- 1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section -->

<!-- Site-wide configuration
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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
