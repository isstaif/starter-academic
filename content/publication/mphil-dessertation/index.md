---
title: "Request Reconstruction in MirageOS Unikernels"
authors:
- admin
date: "2019-6-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-6-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ACS MPhil dissertation
publication_short: 

abstract: Distributed tracing techniques have proven to provide an extremely useful and efficient approach to support a variety of performance management tasks for complex cloud distributed applications. Recently, unikernels have emerged as a promising cloud deployment model for network applications, as they provide a more secure, lightweight and elastic alternative to traditional virtualization options. A combined approach can provide a promising building block to address the autoscaling problem of microservices. In this work, we present an aggregated distributed tracing model that can be used to identify the location of performance bottlenecks in microservice applications. The model enables each service to identify whether it is the root cause of a performance bottleneck or it is one of its descending dependent services. This is achieved based on aggregated measurements received by each service from its directly neighboring services. The aggregation feature allows a flexible tracing infrastructure which enables a local trace analysis at the level of each service as well as at the application level. This can be useful to support the development of both centralized and decentralized autoscaling policies. We present protocol-agnostic generic execution wrappers that allow to implement the tracing model in Mirage unikernels. We leverage the existing tracing module in Mirage and focus on the two essential resources of CPU and network. These wrappers can be used to instrument protocol libraries which are based on synchronous inter-service communication and are written using Lwt lightweight threads. We use these wrappers to instrument the Cohttp library, which enables automatic instrumentation and trace generation for Mirage applications based on HTTP. We illustrate the service-centric analysis capability and show that such an approach can have a minimal overhead on throughput (2-5%) if appropriate sampling techniques are used.


# Summary. An optional shortened abstract.
summary: In my MPhil thesis project, I developed a prorotype of a distributed tracing model for MirageOS unikernel. I identified the essential design dimensions and implementation challenges for the unique single-threaded architecture of MirageOS based single address space and lightweight threads (promises).

tags:
# - Source Themes
featured: true

links:
# - name: Custom Link
#  url: http://example.org
url_pdf: /isstaif_mphil_dissertation.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: '/isstaif_mphil_dissertation_slides.pdf'
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
