---
title: "Explainable Deep Reinforcement Learning for UAV autonomous path planning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lei He
- Nabil Aouf
- Bifeng Song

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Aerospace Science and Technology
publication_short: In *AESCTE*

abstract: Autonomous navigation in unknown environment is still a hard problem for small Unmanned Aerial Vehi-cles (UAVs). Recently, some neural network-based methods are proposed to tackle this problem, however, the trained network is opaque, non-intuitive and difficult for people to understand, which limits the real-world application. In this paper, a novel explainable deep neural network-based path planner is pro-posed for quadrotor to fly autonomously in unknown environment. The navigation problem is modelledas a Markov Decision Process (MDP) and the path planner is trained using Deep Reinforcement Learn-ing (DRL) method in simulation environment. To get better understanding of the trained model, a novel model explanation method is proposed based on the feature attribution. Some easy-to-interpret textual and visual explanations are generated to allow end-users to understand what triggered a particular be-haviour. Moreover, some global analyses are provided for experts to evaluate and improve the trained network. Finally, real-world flight tests are conducted to illustrate that our path planner trained in the simulation is robust enough to be applied in the real environment directly.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Reinforcement Learning, Explainable]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
