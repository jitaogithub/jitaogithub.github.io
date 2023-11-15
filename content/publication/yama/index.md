---
title: 'Yama: Providing Performance Isolation for Black-Box Offloads'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Divyanshu Saxena
  - Brent E. Stephens
  - Aditya Akella

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-10-31T00:00:00Z'
doi: '10.1145/3620678.3624792'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2023 ACM Symposium on Cloud Computing*
publication_short: In *SoCC '23*

abstract: "The sharing of clusters with various on-NIC offloads by high-level entities (users, containers, etc.) has become increasingly common. Performance isolation across these entities is desired because the offloads can become bottlenecks due to the limited capacity of hardware. However, the existing works that provide scheduling and resource management to NIC offloads all require customization of the NIC or offloads, while commodity off-the-shelf NICs and offloads with proprietary implementation have been widely deployed in datacenters. This paper presents Yama, the first solution to enable per-entity isolation in the sharing of such black-box NIC offloads. Yama provides a generic framework that captures a common abstraction to the operation of most offloads, which allows operators to incorporate existing offloads. The framework proactively probes for the performance of the offloads with auxiliary workload and enforces isolation at the initiator side. Yama also accommodates chained offloads. Our evaluation shows that 1) Yama achieves per-entity max-min fairness for various types of offloads and in complicated offload chaining scenarios; 2) Yama quickly converges to changes in equilibrium and 3) Yama adds negligible overhead to application workload."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/yama/yama_paper.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
url_slides: 'publication/yama/yama_slides.pdf'
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
