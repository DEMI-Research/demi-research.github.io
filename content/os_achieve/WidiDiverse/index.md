---
title: 'A Multimodal Entity Linking Dataset (WidiDiverse)'
# title: ''
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

# authors:
#   - Robert Ford

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-04-13T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
publication_short: In *ACL*

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2204.06347'
url_dataset: 'https://github.com/wangxw5/wikiDiverse'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
**Name of the Dataset:** A Multimodal Entity Linking Dataset (WidiDiverse)

**Dataset Introduction:** WIKIDiverse is a high-quality multimodal entity linking (MEL) dataset created to address the limitations of existing MEL datasets, which suffer from limited contextual topics, restricted entity types, simplified mention ambiguity, and poor availability. The dataset consists of 8K image-caption pairs collected from Wikinews, covering over 10 diverse topics including sports, politics, entertainment, disaster, and education. WIKIDiverse contains approximately 16K entity mentions with an average of 2.02 mentions per pair and about 10 words per caption. It includes seven common entity types (Person, Organization, Location, Country, Event, Works, Misc) and uses Wikipedia (~16M entities) as its knowledge base. The dataset was manually annotated with high consistency (Cohen's Kappa of 88.98% for Mention Detection and 83.75% for Entity Linking), providing a more comprehensive and challenging benchmark for MEL research.



**Download Link:** https://github.com/wangxw5/wikiDiverse


**Relevant Paper:** Xuwu Wang, Junfeng Tian, Min Gui, Zhixu Li, Rui Wang, Ming Yan, Lihan Chen, Yanghua Xiao. "WIKIDiverse: A Multimodal Entity Linking Dataset with Diversified Contextual Topics and Entity Types." Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics, 2022.
