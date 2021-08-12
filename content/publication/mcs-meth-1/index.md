---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A method for identifying midlatitude mesoscale convective systems in radar mosaics. Part I: Segmentation and classification"
authors: ["Alex Haberlie", "Walker Ashley"]
date: 2018-01-01T19:51:41-05:00
doi: "https://doi.org/10.1175/JAMC-D-17-0293.1"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-06T19:51:41-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "<i>Journal of Applied Meteorology and Climatology</i>, <b>57</b>, 1575-1598."
publication_short: ""

abstract: "This research evaluates the ability of image-processing and select machine-learning algorithms to identify midlatitude mesoscale convective systems (MCSs) in radar-reflectivity images for the conterminous United States. The process used in this study is composed of two parts: segmentation and classification. Segmentation is performed by identifying contiguous or semicontiguous regions of deep, moist convection that are organized on a horizontal scale of at least 100 km. The second part, classification, is performed by first compiling a database of thousands of precipitation clusters and then subjectively assigning each sample one of the following labels: 1) midlatitude MCS, 2) unorganized convective cluster, 3) tropical system, 4) synoptic system, or 5) ground clutter and/or noise. The attributes of each sample, along with their assigned label, are used to train three machine-learning algorithms: random forest, gradient boosting, and “XGBoost.” Results using a testing dataset suggest that the algorithms can distinguish between MCS and non-MCS samples with a high probability of detection and low probability of false detection. Further, the trained algorithm predictions are well calibrated, allowing reliable probabilistic classification. The utility of this two-step procedure is illustrated by generating spatial frequency maps of automatically identified precipitation clusters that are stratified by using various reflectivity and probabilistic prediction thresholds. These results suggest that machine learning can add value by limiting the amount of false-positive (non-MCS) samples that are not removed by segmentation alone."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://journals.ametsoc.org/downloadpdf/journals/apme/57/7/jamc-d-17-0293.1.xml
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
