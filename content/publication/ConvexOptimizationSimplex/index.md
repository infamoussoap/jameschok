---
title: "Convex Optimization over a probability simplex"
authors:
- admin
- Geoffrey M. Vasil
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Arxiv*"
publication_short: ""

abstract: We propose a new iteration scheme, the Cauchy-Simplex, to optimize convex problems over the probability simplex {w∈ℝn | ∑iwi=1 and wi≥0}. Other works have taken steps to enforce positivity or unit normalization automatically but never simultaneously within a unified setting. This paper presents a natural framework for manifestly requiring the probability condition. Specifically, we map the simplex to the positive quadrant of a unit sphere, envisage gradient descent in latent variables, and map the result back in a way that only depends on the simplex variable. Moreover, proving rigorous convergence results in this formulation leads inherently to tools from information theory (e.g. cross entropy and KL divergence). Each iteration of the Cauchy-Simplex consists of simple operations, making it well-suited for high-dimensional problems. We prove that it has a convergence rate of O(1/T) for convex functions, and numerical experiments of projection onto convex hulls show faster convergence than similar algorithms. Finally, we apply our algorithm to online learning problems and prove the convergence of the average regret for (1) Prediction with expert advice and (2) Universal Portfolios.

# Summary. An optional shortened abstract.
summary: We propose a new iteration scheme to optimize convex problems over the probability simplex.

tags:
- Constrained Optimization
- Convex Hull
- Simplex
- Optimization

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2305.09046
url_code: 'https://github.com/infamoussoap/ConvexHull'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


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
slides: example
---
