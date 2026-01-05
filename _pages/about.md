---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, my name is Vishnu. Thanks for visiting my website. I welcome you!

Currently, I am a faculty member at Mechanical Engineering, SRM University-AP, India. I am interested in numerical simulations of atmospheric flows, turbulence and improving weather forecasting, along with tabletop experiments!

Research Interest
======
I worked on fluid turbulence, transition, and intermittency in pipe flows, with Prof. Pinaki Chakraborty at the Fluid Mechanics Unit (OIST). During an encounter with typhoon while in Okinawa, out of curiosity, I got interested in atmospheric flows and performing some tabletop experiments. This motivated me to write a successful research proposal with a grant of 4 Million JPY with PEREX from OIST Innovation. I could successfully complete the project as its Principal Investigator. I developed an algorithm to estimate wind speed and is now considered for patenting or licensing. This idea will develop a frugal instrument for wind speed estimation, and hopefully an improved resolution local weather forecast with the instrument’s denser deployment. I will be soon pursuing the second phase of this project on numerical weather forecast, with a curious collaborator! (Let me know if you fit here, we can have a chat!)

I did my PhD to understand vortex flows under thermal effects at the Department of Aerospace Engineering, Indian Institute of Technology Madras (IIT Madras). Prof. A. Sameen was my PhD advisor. The study was on Rayleigh Bénard convection with shear due to rotation. From direct numerical simulation (DNS) results, we explored the dynamics of rotating fluid over a heated surface. We established novel scaling laws in heat transfer and developed a parameter with predictive capability.

I also worked with an experimental team under Prof Baburaj Puthenveetil and with Prof Manikandan Mathur, IIT Madras, on an objective criterion (without relying on an ad-hoc value such as in heat flux or temperature) to identify thermal plumes. Previously, I had performed experiments to understand combustion instability in reactive two-phase flows and a laboratory-scale combustor. We applied tools from dynamical systems theory to study the bifurcation characteristics of a combustor during combustion instability. My Master’s thesis advisors were Prof. Preeti Aghalayam and Prof R. I. Sujith, IIT Madras.

My research interests are on the fundamental questions we encounter in nature and to understand things beyond their names and definitions. I have a deep interest in turbulence, thermal convection, rotating flows, oceans, weather and climate, and large-scale atmospheric flows, including questions about how a hurricane forms and develops an eye. I am also interested in conducting tabletop experiments to obtain deeper insights of fluid mechanics. I am also open to dynamical systems’ analysis and applying machine learning to fluid problems, as well as learning the state-of-the-art, including Quantum CFD. I plan to pursue my curiosity during my academic career and beyond. If you find any of these striking to your interest, feel free to drop me an email!

Website last updated: 30 Dec 2025

Vishnu Ravindran, PhD,
Email: 1.vishnur@gmail.com

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
