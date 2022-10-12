---
title: "Understanding Deep Learning Optimization via Benchmarking and Debugging"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

date: "2022-07-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Ph.D. Thesis

abstract: "The central paradigm of machine learning (ML) is the idea that computers can learn the strategies needed to solve a task without being explicitly programmed to do so. The hope is that given data, computers can recognize underlying patterns and figure out how to perform tasks without extensive human oversight. To achieve this, many machine learning problems are framed as minimizing a loss function, which makes optimization methods a core part of training ML models. Machine learning and in particular deep learning is often perceived as a cutting-edge technology, the underlying optimization algorithms, however, tend to resemble rather simplistic, even archaic methods. Crucially, they rely on extensive human intervention to successfully train modern neural networks. One reason for this tedious, finicky, and lengthy training process lies in our insufficient understanding of optimization methods in the challenging deep learning setting. As a result, training neural nets, to this day, has the reputation of being more of an art form than a science and requires a level of human assistance that runs counter to the core principle of ML. Although hundreds of optimization algorithms for deep learning have been proposed, there is no widely agreed-upon protocol for evaluating their performance. Without a standardized and independent evaluation protocol, it is difficult to reliably demonstrate the usefulness of novel methods. In this thesis, we present strategies for quantitatively and reproducibly comparing deep learning optimizers in a meaningful way. This protocol considers the unique challenges of deep learning such as the inherent stochasticity or the crucial distinction between learning and pure optimization. It is formalized and automatized in the Python package DeepOBS and allows fairer, faster, and more convincing empirical comparisons of deep learning optimizers. Based on this benchmarking protocol, we compare fifteen popular deep learning optimizers to gain insight into the field's current state. To provide evidence-backed heuristics for choosing among the growing list of optimization methods, we extensively evaluate them with roughly 50,000 training runs. Our benchmark indicates that the comparably traditional Adam optimizer remains a strong but not dominating contender and that newer methods fail to consistently outperform it. In addition to the optimizer, other causes can impede neural network training, such as inefficient model architectures or hyperparameters. Traditional performance metrics, such as training loss or validation accuracy, can show if a model is learning or not, but not why. To provide this understanding and a glimpse into the black box of neural networks, we developed Cockpit, a debugging tool specifically for deep learning. It combines novel and proven observables into a live monitoring tool for practitioners. Among other findings, Cockpit reveals that well-tuned training runs consistently overshoot the local minimum, at least for significant portions of the training. The use of thorough benchmarking experiments and tailored debugging tools improves our understanding of neural network training. In the absence of theoretical insights, these empirical results and practical tools are essential for guiding practitioners. More importantly, our results show that there is a need and a clear path for fundamentally different optimization methods to make deep learning more accessible, robust, and resource-efficient."

# Summary. An optional shortened abstract.
summary: Ph.D. Thesis

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://publikationen.uni-tuebingen.de/xmlui/bitstream/handle/10900/131710/Thesis_FrankSchneider_digital.pdf?sequence=1&isAllowed=y'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://publikationen.uni-tuebingen.de/xmlui/handle/10900/131710'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false
---
