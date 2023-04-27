---
title: "Late-Phase Second-Order Training"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lukas Tatzel
- Philipp Hennig
- admin

date: "2022-12-30T00:00:00"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-30T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *HITY Workshop (NeurIPS) 2022*
publication_short: In *HITY Workshop 2022*

abstract: "Towards the end of training, stochastic first-order methods such as SGD and Adam go into diffusion and no longer make significant progress. In contrast, Newton-type methods are highly efficient close to the optimum, in the deterministic case. Therefore, these methods might turn out to be a particularly efficient tool for the final phase of training in the stochastic deep learning context as well. In our work, we study this idea by conducting an empirical comparison of a second-order Hessian-free optimizer and different first-order strategies with learning rate decays for late-phase training. We show that performing a few costly but precise second-order steps can outperform first-order alternatives in wall-clock runtime."

# Summary. An optional shortened abstract.
summary: We show that performing a few costly but precise second-order steps can outperform first-order alternatives in wall-clock runtime.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=C3hL1sbz5Vf'
url_code: 'https://github.com/ltatzel/PyTorchHessianFree'
url_preprint: 'https://openreview.net/forum?id=C3hL1sbz5Vf'
url_dataset: ''
url_poster: 'https://neurips.cc/media/PosterPDFs/NeurIPS%202022/56640.png?t=1668154807.7827299'
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
---
