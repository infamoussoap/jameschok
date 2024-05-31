---
title: "Rational function approximation with normalized positive denominators"
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

abstract: Rational function approximations provide a simple but flexible alternative to polynomial approximation, allowing one to capture complex non-linearities without oscillatory artifacts. However, there have been few attempts to use rational functions on noisy data due to the likelihood of creating spurious singularities. To avoid the creation of singularities, we use Bernstein polynomials and appropriate conditions on their coefficients to force the denominator to be strictly positive. While this reduces the range of rational polynomials that can be expressed, it keeps all the benefits of rational functions while maintaining the robustness of polynomial approximation in noisy data scenarios. Our numerical experiments on noisy data show that existing rational approximation methods continually produce spurious poles inside the approximation domain. This contrasts our method, which cannot create poles in the approximation domain and provides better fits than a polynomial approximation and even penalized splines on functions with multiple variables. Moreover, guaranteeing pole-free in an interval is critical for estimating non-constant coefficients when numerically solving differential equations using spectral methods. This provides a compact representation of the original differential equation, allowing numeric solvers to achieve high accuracy quickly, as seen in our experiments.

# Summary. An optional shortened abstract.
summary: We propose a new rational function approximation method that guarantees free of poles in the approximation domain.

tags:
- Rational Function approximation
- Suprious poles
- Spectral methods
- Optimization
- Derivative penalty

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2310.12053
url_code: 'https://github.com/infamoussoap/RationalFunctionApproximation'
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
