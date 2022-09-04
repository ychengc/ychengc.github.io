---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website 
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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

Research Interests
------
* Data management on new hardware
* AI4DB and DB4AI
* Data cleaning, data integration, data discovery
* Spatial data management

Selected Publications (* corresponding author)
------
1. **C Yang**, L Chen, H Wang, S Shang, R Mao, X Zhang. Dynamic set similarity join: an update log based approach. IEEE Transactions on Knowledge and Data Engineering, 1-14, 2021.
2. **C Yang**, D Deng, S Shang, F Zhu, L Liu, L Shao. Internal and external memory set containment join. The VLDB Journal, 2021, 30(3): 447-470.
3. **C Yang**, L Chen, H Wang, S Shang. Towards efficient selection of activity trajectories based on diversity and coverage. AAAI, 2021, 35(1): 689-696.
4. **C Yang**, D Deng, S Shang, L Shao. Efficient locality-sensitive hashing over high-dimensional data streams. ICDE, 2020: 1986-1989.
5. H Wang, **C Yang***, X Zhang, X Gao. Efficient locality-sensitive hashing over high-dimensional streaming data. Neural Computing and Applications, 2020: 1-14.
6. P Jin, **C Yang**, X Wang, L Yue, D Zhang. SAL-hashing: a self-adaptive linear hashing index for SSDs. IEEE Transactions on Knowledge and Data Engineering, 2020, 32(3): 519-532.
7. L Chen, S Shang, **C Yang**, J Li. Spatial keyword search: a survey. GeoInformatica, 2020, 24(1): 85-106.
8. **C Yang**, L Chen, S Shang, F Zhu, L Liu, L Shao. Toward Efficient Navigation of Massive-Scale Geo-Textual Streams. IJCAI, 2019: 4838-4845.
9. D Deng, **C Yang***, S Shang***, F Zhu, L Liu, L Shao. LCJoin: set containment join via list crosscutting. ICDE, 2019: 362-373.
10. P Jin, **C Yang**, C.S. Jensen, P Yang, L Yue. Read/write-optimized tree indexing for solid-state drives. The VLDB Journal, 2016, 25(5): 695-717.
11. **C Yang**, P Jin, L Yue, D Zhang. Self-adaptive linear hashing for solid state drives. ICDE, 2016: 433-444.
12. L Li, P Jin, **C Yang**, Z Wu, L Yue. Optimizing B+-tree for PCM-based hybrid memory. EDBT, 2016: 662-663.
13. **C Yang**, P Jin, L Yue, P Yang. Efficient buffer management for tree indexes on solid state drives. International Journal of Parallel Programming, 2016, 44(1): 5-25. (best paper of NPC 2014)
