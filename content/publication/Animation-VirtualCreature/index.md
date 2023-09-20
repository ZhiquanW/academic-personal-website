---
title: 'Co-design of embodied neural intelligence via constrained evolution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Bedrich Benes
  - Ahmed H. Qureshi
  - Christos Mousas

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-051-01T00:00:00Z'
# doi: 'asdfasdfasdfasd'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv preprint arXiv:2205.10688
publication_short: arXiv preprint arXiv:2205.10688

abstract: We introduce a novel co-design method for autonomous moving agents’ shape attributes and locomotion by combining deep reinforcement learning and evolution with user control. Our main inspiration comes from evolu- tion, which has led to wide variability and adaptation in Nature and has the potential to significantly improve design and behavior simultaneously. Our method takes an input agent with optional simple constraints such as leg parts that should not evolve or allowed ranges of changes. It uses physics-based simulation to determine its locomotion and finds a behavior policy for the input design, later used as a baseline for comparison. The agent is then randomly modified within the allowed ranges creating a new generation of several hundred agents. The generation is trained by trans- ferring the previous policy, which significantly speeds up the training. The best-performing agents are selected, and a new generation is formed using their crossover and mutations. The next generations are then trained until satisfactory results are reached. We show a wide variety of evolved agents, and our results show that even with only 10% of changes, the overall per- formance of the evolved agents improves 50%. If more significant changes to the initial design are allowed, our experiments’ performance improves even more to 150%. Contrary to related work, our co-design works on a single GPU and provides satisfactory results by training thousands of agents within one hour.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/pdf/2205.10688.pdf
# url_code: ''
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://www.youtube.com/watch?v=stCSTDlMjI4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
