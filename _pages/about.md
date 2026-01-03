---
permalink: /
title: "Hello! I’m Sang Hyun"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m Sang Hyun, a PhD student in mathematics education at the University of Auckland in New Zealand. My thesis explores students’ learning experiences in tertiary-level mathematics and is supervised by Associate Professor Tanya Evans and Dr Ofer Marmur. My project is supported by a University of Auckland Doctoral Scholarship.

My research focuses on how students make sense of mathematics and how learning emerges through social and contextual factors in university settings. My work primarily uses quantitative methods and is largely exploratory, and I am increasingly interested in incorporating mixed-methods approaches. Situated at the intersection of mathematics education, educational psychology, and cognitive science, my research draws on theories and frameworks from all three domains. During my PhD, I have also worked as a Graduate Teaching Assistant in undergraduate mathematics courses at the University of Auckland.

Outside of academia, I am passionate about music and music education. I play cornet in Auckland City Brass and have performed in a range of other ensembles.





A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).


Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**


