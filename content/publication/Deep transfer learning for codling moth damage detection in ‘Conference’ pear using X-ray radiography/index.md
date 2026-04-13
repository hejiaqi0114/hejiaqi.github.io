---
title: 'Deep transfer learning for codling moth damage detection in ‘Conference’ pear using X-ray radiography'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tim Belien
  - Ammar Alhmedi
  - Ann Schenk 
  - Dany Bylemans 
  - Pieter Verboven
  - Bart Nicolai

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-12-19T00:00:00Z'
doi: '10.1016/j.foodcont.2025.111923'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Food Control
publication_short: None

abstract: Early detection of pest infestation is essential for ensuring postharvest fruit quality and compliance with export standards. This study investigates deep transfer learning for detecting codling moth (Cydia pomonella) larval damage in ‘Conference’ pears using non-destructive X-ray radiography. Data were collected from both controlled laboratory and field infestations across multiple growing seasons, and augmented via a radiographic simulation framework. We evaluated three convolutional neural networks (ResNet50, DenseNet121, and InceptionV3) under three transfer learning strategies (feature extractor, partial, and full fine-tunning) using pretrained weights from ImageNet, RadImageNet, or random initialization. A classical machine learning baseline combining adaptive thresholding segmentation and handcrafted features with Support Vector Machine (SVM), k-Nearest Neighbors (kNN), and Logistic Regression (LR), was also implemented for comparison. Transfer learning strategy had the greatest influence on model performance, with full fine-tuning yielding the highest accuracy. Pretrained weights, especially from ImageNet, consistently improved performance over random initialization. The differences between model architectures were smaller under full fine-tunning and pretrained weights from ImageNet. The top-performing configuration of ResNet50 with ImageNet weights and full fine-tuning, reached 91–97 % accuracy across internal test sets and showed 20 % improvement in accuracy, precision and recall compared to the benchmark method. Performance remained robust on an independent test set, with an approximately 10 % improvement over the benchmark method. Guided Grad-CAM heatmaps confirmed that the infestation regions were correctly localized by deep learning models, supporting modal interpretability and reliability. These findings underline the potential of deep transfer learning for accurate and interpretable detection of internal pest damage in pear fruit and support the deployment of automated X-ray-based inspection systems in postharvest quality control workflows.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# slides: example

---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->