---
title: "A comprehensive benchmarking of WGS-based deletion structural variant callers"
authors:
- Varuni Sarwal
- Sebastian Niehus
- Ram Ayyala
- Minyoung Kim
- Aditya Sarkar
- admin
- Angela Lu
- Neha Rajkumar
- Nicholas Darci-Maher
- Russell Littman
- Karishma Chhugani
- Arda Soylev
- Zoia Comarova
- Emily Wesel
- Jacqueline Castellanos
- Rahul Chikka
- Margaret G Distler
- Eleazar Eskin
- Jonathan Flint
- Serghei Mangul
date: "2022-06-27T00:00:00Z"
doi: "https://doi.org/10.1093/bib/bbac221"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Briefings in Bioinformatics*"
publication_short: ""

abstract: Advances in whole-genome sequencing (WGS) promise to enable the accurate and comprehensive structural variant (SV) discovery. Dissecting SVs from WGS data presents a substantial number of challenges and a plethora of SV detection methods have been developed. Currently, evidence that investigators can use to select appropriate SV detection tools is lacking. In this article, we have evaluated the performance of SV detection tools on mouse and human WGS data using a comprehensive polymerase chain reaction-confirmed gold standard set of SVs and the genome-in-a-bottle variant set, respectively. In contrast to the previous benchmarking studies, our gold standard dataset included a complete set of SVs allowing us to report both precision and sensitivity rates of the SV detection methods. Our study investigates the ability of the methods to detect deletions, thus providing an optimistic estimate of SV detection performance as the SV detection methods that fail to detect deletions are likely to miss more complex SVs. We found that SV detection tools varied widely in their performance, with several methods providing a good balance between sensitivity and precision. Additionally, we have determined the SV callers best suited for low- and ultralow-pass sequencing data as well as for different deletion length categories.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://academic.oup.com/bib/article-pdf/23/4/bbac221/46580990/bbac221.pdf'
url_code: 'https://github.com/Mangul-Lab-USC/benchmarking_SV'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->