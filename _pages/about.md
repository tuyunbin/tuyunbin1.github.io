---
permalink: /
title: Yunbin Tu's Homepage
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second year Ph.D. student from School of Computer Science & Technology (SCST), University of Chinese Academy of Sciences (UCAS). My research interest focuses on vision-and-language, such as video captioning and change captioning. 

I am very fortunate to be advised by [Prof. Li Su](https://people.ucas.ac.cn/~suli) from UCAS, and [A.P. Liang Li](https://vipl.ict.ac.cn/people/lliang/) from ICT, CAS. I received my master's degree from Kunming University of Science and Technology in 2022, advised by [Prof. Zhengtao Yu](https://xzy.kmust.edu.cn/info/1159/1311.htm). I received my bachelor's degree From Hangzhou Dizi University in 2018, advised by [Prof. Chenggang Yan](https://auto.hdu.edu.cn/2019/0621/c3803a96028/page.htm). I am also lucky to have opportunities to collaborate with [Xishan Zhang](http://www.ict.cas.cn/sourcedb_2018_ict_cas/cn/jssrck/202003/t20200310_5509322.html)  (A.P. at ICT, CAS) and [Xingzheng Wang](https://cmce.szu.edu.cn/info/1429/3786.htm)  (A.P. at Shenzhen University).  

[Google Scholar](https://scholar.google.com/citations?hl=en&user=T-T1X0QAAAAJ) / [Semantic Scholar](https://www.semanticscholar.org/author/Yunbin-Tu/26994223) / [DBLP](https://dblp.uni-trier.de/pid/207/1931.html)

Recent News
======
- 2023.07: A paper is accepted by ICCV 2023.
- 2023.03 A paper is accepted by IEEE TIP.
- 2023.02 A paper is accepted by IEEE TMM.
- 2023.01 A paper is accepted by IEEE TMM.

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
