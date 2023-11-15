---
title: 'Resilient Baseband Processing in Virtualized RANs with Slingshot'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikita Lazarev
  - admin_eq_contrib
  - Anuj Kalia
  - Daehyeok Kim
  - Ilias Marinos
  - Francis Y. Yan
  - Christina Delimitrou
  - Zhiru Zhang
  - Aditya Akella

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-01T00:00:00Z'
doi: '10.1145/3603269.3604841'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM SIGCOMM 2023 Conference*
publication_short: In *SIGCOMM '23*

abstract: "In cellular networks, there is a growing adoption of virtualized radio access networks (vRANs), where operators are replacing the traditional specialized hardware for RAN processing with software running on commodity servers. Today's vRAN deployments lack resilience, since there is no support for vRAN failover or upgrades without long service interruptions. Enabling these features for vRANs is challenging because of their strict real-time latency requirements and black-box nature. Slingshot is a new system that transparently provides resilience for the vRAN's most performance-critical layer: the physical layer (PHY). We design new techniques for realtime workload migration with fast RAN protocol middle-boxes, and realtime RAN failure detection. A key insight in our design is to view the transient disruptions from resilience events to RAN computation state and I/O similarly to regular wireless signal impairments, and leverage the inherent resilience of cellular networks to these events. Experiments with a state-of-the-art 5G vRAN testbed show that Slingshot handles PHY failover with no disruption to video conferencing, and under 110 ms disruption to a TCP connection, and it also enables zero-downtime upgrades."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/slingshot/slingshot_paper.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
url_slides: 'publication/slingshot/slingshot_slides.pdf'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

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
{{% /callout %}} -->
<!-- 
Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
