---
title: "Towards Accelerating Data Intensive Application's Shuffle Process Using SmartNICs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiaxin Lin
  - admin
  - Xiangpeng Hao
  - Hokeun Cha
  - Yanfang Le
  - Xiangyao Yu
  - Aditya Akella

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-22T00:00:00Z'
doi: '10.1145/3589980'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM on Measurement and Analysis of Computing Systems*
publication_short: In *SIGMETRICS '23*

abstract: "The wide adoption of the emerging SmartNIC technology creates new opportunities to offload application-level computation into the networking layer, which frees the burden of host CPUs, leading to performance improvement. Shuffle, the all-to-all data exchange process, is a critical building block for network communication in distributed data-intensive applications and can potentially benefit from SmartNICs.\n\n
In this paper, we develop SmartShuffle, which accelerates the data-intensive application's shuffle process by offloading various computation tasks into the SmartNIC devices. SmartShuffle supports offloading both low-level network functions, including data partitioning and network transport, and high-level computation tasks, including filtering, aggregation, and sorting. SmartShuffle adopts a coordinated offload architecture to make sender-side and receiver-side SmartNICs jointly contribute to the benefits of shuffle computation offload. SmartShuffle carefully manages the tight and time-varying computation and memory constraints on the device. We propose a liquid offloading approach, which dynamically migrates operators between the host CPU and the SmartNIC at runtime such that resources in both devices are fully utilized.\n\n
We prototype SmartShuffle on the Stingray SoC SmartNICs and plug it into Spark. Our evaluation shows that SmartShuffle improves host CPU efficiency and I/O efficiency with lower job completion time. SmartShuffle outperforms Spark, and Spark RDMA by up to 40% on TPC-H."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/smartshuffle/smartshuffle_paper.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
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
