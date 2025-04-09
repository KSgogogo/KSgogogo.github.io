---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a lecturer at Wuhan University of Science and Technology.

Since 2013, I have been studying at the School of Computer Science, Wuhan University, where I earned my Bachelor's and Ph.D. degrees, supervied by Professor Tieyun Qian (钱铁云). 

My research interests focus on recommender systems, with an emphasis on sequential recommendation, Point-of-Interest (POI) recommendation, and generative recommendation. I have published 10+ papers at well-known conferences and journals, such as AAAI, EMNLP, ACM TOIS, and IEEE TKDE. In the future, I aim to explore the potential applications of large language models to the POI recommendation or urban computing. 

 If you are interested in my study, please feel free to email me at sunke@wust.edu.cn.

Publications
======
*Adaption-of-thought: Learning question difficulty improves large language models for reasoning. Mayi Xu, Yongqi Li, **Ke Sun**, and Tieyun Qian. EMNLP2024 (CCF-B)
*City Matters! A Dual-Target Cross-City Sequential POI Recommendation Model. **Ke Sun**, Chenliang Li, and Tieyun Qian. TOIS2024 (CCF-A)
*Dynamic Open-book Prompt for Conversational Recommender System. Xuan Ma, Tieyun Qian, and **Ke Sun**. EMNLP2023 Findings (CCF-B)
*Pre-training across different cities for next poi recommendation. **Ke Sun**, Tieyun Qian, Chenliang Li, Xuan Ma, Qing Li, Ming Zhong, Yuanyuan Zhu, and Mengchi Liu. TWEB2023 (CCF-B)
*Cold-Start Multi-hop Reasoning by Hierarchical Guidance and Self-verification. Mayi Xu, **Ke Sun**, Yongqi Li, and Tieyun Qian. ECML2023 (CCF-B)
*Towards more effective encoders in pre-training for sequential recommendation. **Ke Sun**, Tieyun Qian, Ming Zhong, and Xuhui Li. WWWJ2023 (CCF-B)
*Intent disentanglement and feature self-supervision for novel recommendation. Tieyun Qian, Yile Liang, Qing Li, Xuan Ma, **Ke Sun**, Zhiyong Peng. TKDE2022 (CCF-A)
*Enhancing graph convolution network for novel recommendation. Xuan Ma, Tieyun Qian, Yile Liang, **Ke Sun**, Hang Yun, and Mi Zhang. DASFAA2022 (CCF-B)
*Context-aware seq2seq translation model for sequential recommendation. **Ke Sun**, Tieyun Qian, Xu Chen, Ming Zhong. INS2021 (CCF-B)
*Where to go next: Modeling long-and short-term user preferences for point-of-interest recommendation. **Ke Sun**, Tieyun Qian, Tong Chen, Yile Liang, Quoc Viet Hung Nguyen, and Hongzhi Yin. AAAI2020 (CCF-A)
*What Can History Tell Us? Identifying Relevant Sessions for Next-Item Recommendation. **Ke Sun**, Tieyun Qian, Hongzhi Yin, Tong Chen, Yiqi Chen, and Ling Chen. CIKM2019 (CCF-B)
*"Bridge" Enhanced Signed Directed Network Embedding. Yiqi Chen, Tieyun Qian, Huan Liu, and **Ke Sun**. CIKM2018 (CCF-B)
*Exploiting user and item attributes for sequential recommendation. **Ke Sun** and Tieyun qian. ICONIP2018 (CCF-C)

Educations
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
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

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
