---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently a Data Scientist in Tesco's Personalisation team, leading the delivery of [Your Clubcard Prices](https://www.thesun.co.uk/money/33181430/tesco-clubcard-change-your-prices-extra-money-discounts/). Broadly, I am excited about delivering real-world business value through modelling problems under the different lenses of reinforcement learning, [systems engineering](https://www.nasa.gov/wp-content/uploads/2018/09/nasa_systems_engineering_handbook_0.pdf), and design thinking. Particularly, with LLMs bringing more general capabilities to RL, I'm excited about the future of agentic AI (and the comeback of multi-agent RL!).

**Research.** I completed my PhD from the [University of Cambridge](https://www.linkedin.com/company/supply-chain-ai-lab) where my research focused on deep multi-agent reinforcement learning for real-world settings. At a high level, I trained agents to **negotiate** with one another in mixed-motive settings, placing heavy emphasis on rigorously evaluating learnt agent behaviour. More broadly, the intersection of MARL and game theory allows for truly scalable methods. I wish I did my PhD post-ChatGPT, but I'm excited to watch the additional flavour agentic AI will bring to negotiation — particularly multi-issue and multi-lateral.

For an up-to-date list of my publications at [NeurIPS \[1](https://arxiv.org/pdf/2310.17458), [2\]](https://openreview.net/pdf?id=7T4YMOj7MS), [ICML](https://openreview.net/pdf?id=adcvCs3qA1), [Oral at AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/30067), [Transportation Research](https://www.sciencedirect.com/science/article/pii/S0968090X23003662), and [patent](https://patents.google.com/patent/US20240338418A1/en), see my [Google Scholar](https://scholar.google.com/citations?user=MutMC4kAAAAJ&hl=en).

**Previously.** I completed an internship at [J.P. Morgan AI Research](https://www.jpmorgan.com/technology/artificial-intelligence) where I applied deep reinforcement learning towards inventory management, delivering \$XX millions a year in cost savings. Prior to my PhD, I was a Data Engineer at [Rolls-Royce's R² Data Labs](https://www.rolls-royce.com/media/press-releases/2017/12-12-2017-rr-launches-r2-data-labs-to-accelerate-data-innovation.aspx) where I worked on [predictive maintenance](https://www.rolls-royce.com/media/our-stories/discover/2019/trent-to-the-limit-how-rr-readies-its-engines-for-extreme-environments.aspx) analysing TBs of environmental data such as sulphur. I was also a Research Engineer working on computer vision for intellectual property within the [Future Intelligence Team](https://www.rolls-royce.com/country-sites/sea/our-stories/2021/tapping-ai-technologies-to-create-solutions-of-tomorrow.aspx). At Rolls-Royce, I was taught [systems engineering](https://www.nasa.gov/wp-content/uploads/2018/09/nasa_systems_engineering_handbook_0.pdf), which is mandatory training for every engineer at Rolls-Royce. It helps avoid solutioneering (getting carried away with technical details, instead of delivering what stakeholders want — I'm looking at you, Agentic AI). This has revolutionised the way I tackle problems and approach innovation.

Side Projects
=======

1) Creating my own AI Scientist (Multi-Agent LLMs & RAG) to help me keep up to date with AI. Write-up coming soon!

2) Neural rendering / Gaussian splats of my wedding ceremony, taken from 6 different cameras! Imagine being able to re-live that day in virtual reality thanks to ML!


<!-- 
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
