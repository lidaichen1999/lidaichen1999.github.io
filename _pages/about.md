---
permalink: /
title: "Welcome to LI Daichen's homepage:)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

 <font color=Red>I'm interested in Natural Language Processing and Cyber-Security. I am looking for an opportunity to study for a PhD/MPhil starting in 2022.</font>
<br>

Education
======

<div style="float:left;"><font size=4> China University of Geoscience, Beijing</font></div><div style="float:right;"><i>Sep 2017 - Jun 2021</i></div>

<br>
Bachelor, Information Management and Information Systems 
Overall GPA:3.45/4    WAM:87.42/100
Core Courses：Data Structure, System Analysis and Design, Java Program Design, Oracle Database Application, Management Information System, Information Security Management, Data Mining and Business Intelligence


RESEARCH EXPERIENCE
======
### Design of Library Resource Sharing Platform in Colleges and Universities

<div style="float:left;"><font size=4>Team Leader</font></div><div style="float:right;"><i>Nov 2019 - Apr 2021</i></div>

<br>

In order to solve the problem of non intercommunication of university books, a university book database in Beijing was designed by using MySQL. The function of querying books among universities is completed by calling API interface.

### Research on the Evolution Law of Network Public Opinion on Inversion Events

<div style="float:left;"><font size=4>Team Leader</font></div><div style="float:right;"><i>Nov 2018 - Apr 2020</i></div>

<br>

Used Python to collect the micro blog review data and analyzed the text, then set up multiple time nodes to determine thetrend of reverse time public opinion. The paper concluded that the response speed of public opinion has a certain lag.

### Design of Task-based Data Acquisition Platform

<div style="float:left;"><font size=4>Member</font></div><div style="float:right;"><i>Nov 2018 - Nov 2019</i></div>

<br>

Used Adobe Dreamweaver to build a web version of the task publishing reward platform and used sketch to design the interaction of the page.

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
