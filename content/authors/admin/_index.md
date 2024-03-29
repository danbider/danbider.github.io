---
# Display name
title: Dan Biderman

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: ML & Comp Neuro PhD Candidate

# Organizations/Affiliations to show in About widget
organizations:
  - name: Center for Theoretical Neuroscience @ Columbia U
    url: https://ctn.zuckermaninstitute.columbia.edu/
  - name: MosaicML research team @ Databricks
    url: https://www.mosaicml.com/

# Short bio (displayed in user profile at end of posts)
bio: Building ML models that learn with limited data and limited compute. Using them to understand brain and behavior.

# Interests to show in About widget
interests:
  - Gaussian Processes and state-space models.
  - LLM finetuning, evaluation, data curation, and codegen.
  - Pose estimation and inverse control problems.
  - Computational Neuroscience and Neuroethology.

# Education to show in About widget
education:
  courses:
    - course: PhD in Computational Neuroscience
      institution: Columbia University
      year: 2018-
    - course: MA in Cognitive Science
      institution: Tel Aviv University
      year: 2018
    - course: The Adi Lautman Interdisciplinary Program for Outstanding Students (Cog. Sci., Math, Neurobio.)
      institution: Tel Aviv University
      year: 2013-2017

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: "/#contact"
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/dan_biderman
  - icon: graduation-cap # Alternatively, use `google-scholar` icon from `ai` icon pack
    icon_pack: fas
    link: https://scholar.google.com/citations?user=6WFbVJUAAAAJ&hl=en
  - icon: github
    icon_pack: fab
    link: https://github.com/danbider
  # - icon: linkedin
  #   icon_pack: fab
  #   link: https://www.linkedin.com/

# Link to a PDF of your resume/CV.
# To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.toml`,
# and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: uploads/resume.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: dan.biderman@columbia.edu

# Highlight the author in author lists? (true/false)
highlight_name: true
---

I build resource-constrained machine learning (ML) systems for science -- in vision, timeseries, and text domains – fusing approaches from statistical ML and CS systems.

I am currently a final-year PhD candidate advised by [John Cunningham](https://stat.columbia.edu/~cunningham/) and working closely with [Liam Paninski](http://www.stat.columbia.edu/~liam/). I am also a part-time NLP researcher at MosaicML/Databricks, under [Jonathan Frankle](http://www.jfrankle.com/), where I work on LLM parameter-efficient finetuning, evaluation, and data, with an emphasis on code generation.

In my primary PhD work, I develop semi-supervised computer vision systems for tracking animals in videos, reducing the amount of labeled data needed for the task and improving generalization. Our package [lightning-pose](https://github.com/danbider/lightning-pose) ([bioRxiv, 2023; under review](https://www.biorxiv.org/content/10.1101/2023.04.28.538703v1)) is widely used in science and industry. I have also tackled this problem via probabilistic representation learning ([NeurIPS, 2019](https://papers.nips.cc/paper/2019/hash/a10463df69e52e78372b724471434ec9-Abstract.html), [PLOS Comp. Biol., 2021](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009439)), 3D vision, and physical simulation ([NeurIPS DiffCVGP, 2020](https://montrealrobotics.ca/diffcvgp/assets/papers/2.pdf)). In a second line of work, I focus on the computational efficiency and inductive biases of Gaussian processes ([ICML, 2021](https://arxiv.org/pdf/2102.06695.pdf)). My ongoing NLP work at MosaicML addresses questions of knowledge acquisition and extinction and its interaction with parameter-efficient finetuning methods (more soon!).

Throughout my PhD, I collaborated closely with [Lightning AI](https://lightning.ai/), named [a Lightning Ambassador](https://lightning.ai/ambassador-program/), and a [featured developer in their first DevCon, June 2022](https://www.youtube.com/watch?v=W-TyfNUABhw).

{{< icon name="download" pack="fas" >}} Here is my {{< staticref "uploads/resume.pdf" "newtab" >}}CV{{< /staticref >}}.
