---
title: "Benchmarking Neural Network Training Algorithms"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- George E. Dahl
- admin
- Zachary Nado
- Naman Agarwal
- Chandramouli Shama Sastry
- Philipp Hennig
- Sourabh Medapati
- Runa Eschenhagen
- Priya Kasimbeg
- Daniel Suo
- Juhan Bae
- Justin Gilmer
- Abel L. Peirson
- Bilal Khan
- Rohan Anil
- Mike Rabbat
- Shankar Krishnan
- Daniel Snider
- Ehsan Amid
- Kongtao Chen
- Chris J. Maddison
- Rakshith Vasudev
- Michal Badura
- Ankush Garg
- Peter Mattson

date: "2023-06-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: arXiv preprint
publication_short: arXiv

abstract: "Training algorithms, broadly construed, are an essential part of every deep learning pipeline. Training algorithm improvements that speed up training across a wide variety of workloads (e.g., better update rules, tuning protocols, learning rate schedules, or data selection schemes) could save time, save computational resources, and lead to better, more accurate, models. Unfortunately, as a community, we are currently unable to reliably identify training algorithm improvements, or even determine the state-of-the-art training algorithm. In this work, using concrete experiments, we argue that real progress in speeding up training requires new benchmarks that resolve three basic challenges faced by empirical comparisons of training algorithms: (1) how to decide when training is complete and precisely measure training time, (2) how to handle the sensitivity of measurements to exact workload details, and (3) how to fairly compare algorithms that require hyperparameter tuning. In order to address these challenges, we introduce a new, competitive, time-to-result benchmark using multiple workloads running on fixed hardware, the AlgoPerf: Training Algorithms benchmark. Our benchmark includes a set of workload variants that make it possible to detect benchmark submissions that are more robust to workload changes than current widely-used methods. Finally, we evaluate baseline submissions constructed using various optimizers that represent current practice, as well as other optimizers that have recently received attention in the literature. These baseline results collectively demonstrate the feasibility of our benchmark, show that non-trivial gaps between methods exist, and set a provisional state-of-the-art for future benchmark submissions to try and surpass."

# Summary. An optional shortened abstract.
summary: We motivate, present, and justify our new AlgoPerf Training Algorithms benchmark.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2306.07179.pdf'
url_preprint: 'https://arxiv.org/abs/2306.07179'
url_code: 'https://github.com/mlcommons/algorithmic-efficiency'
url_dataset: ''
url_poster: ''
url_project: 'https://mlcommons.org/en/groups/research-algorithms/'
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
