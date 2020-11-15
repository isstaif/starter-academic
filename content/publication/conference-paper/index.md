---
title: "Performance Model of Apache Cassandra Under Heterogeneous Workload Using the Quantitative Verification Approach"
authors:
- admin
- Nizar Alhafez 
date: "2018-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Source Themes Conference*
publication_short: In *STC*

abstract: We report our experience using PRISM, a leading quantitative verification engine, to formulate a performance model of Apache Cassandra, a popular NoSQL database, under a simple form of hybrid operational/analytical workload, since such heterogeneous workloads have shown to have significant implications for the deployment and elastic strategies of these databases. Some current literature suggest that, compared to classical performance modelling tools, quantitative verification provides a more rigorous analysis framework. We aim to explore the effectiveness and applicability of this approach in practice which we identify as relevant to our use case. We present a partial model of a single Cassandra node that predicts its maximum throughput under various system and workload parameters and validate this model experimentally. Furthermore, we show the limitations of extending this model using PRISM to address other interesting properties, identifying the need for scalable analytical modelling approaches for realistic highly concurrent systems under heterogeneous workloads. 


# Summary. An optional shortened abstract.
summary: This was my first Systems research work where I characterized the performance of NoSQL under hybrid analytical/transactional workload, and demonstrated the challanges of building analytical models of real-world systems

tags:
- Source Themes
featured: true

links:
# - name: Link
#  url: https://link.springer.com/chapter/10.1007%2F978-3-030-02227-3_7
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

# {{% alert note %}}
# Click the *Cite* button above to demo the feature to enable visitors to #import publication metadata into their reference management software.
# {{% /alert %}}

# {{% alert note %}}
# Click the *Slides* button above to demo Academic's Markdown slides feature.
# {{% /alert %}}

