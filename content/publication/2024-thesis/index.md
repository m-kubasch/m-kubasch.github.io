---
title: "Approximation of stochastic models for epidemics on large multi-level graphs"
authors:
- admin
date: "2024-07-10"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: "PhD Thesis"
publication_short: ""

abstract: ""

1. tags:
- Publications
featured: false

links:
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
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

share: false
---

**Abstract**: We study an *SIR* model with two levels of mixing, namely a uniformly mixing global level, and a local level with two layers of household and workplace contacts, respectively. More precisely, we aim at proposing reduced models which approximate well the epidemic dynamics at hand, while being more prone to mathematical analysis and/or numerical exploration.

We investigate the epidemic impact of the workplace size distribution. Our simulation study shows that if the average workplace size is kept fixed, the variance of the workplace size distribution is a good indicator of its influence on key epidemic outcomes. In addition, this allows to design an efficient teleworking strategy. Next, we demonstrate that a deterministic, uniformly mixing *SIR* model calibrated using the epidemic growth rate yields a parsimonious approximation of the household-workplace model. 

However, the accuracy of this reduced model deteriorates over time and lacks theoretical guarantees. Hence, we study the large population limit of the stochastic household-workplace model, which we formalize as a measure-valued process with continuous state space. In a general setting, we establish convergence to the unique deterministic solution of a measure-valued equation. In the case of exponentially distributed infectious periods, a stronger reduction to a finite dimensional dynamical system is obtained. 

Further, in order to gain a finer insight on the impact of the model parameters on the performance of both reduced models, we perform a sensitivity study. We show that the large population limit of the household-workplace model can approximate well the epidemic even if some assumptions on the contact network are relaxed. Similarly, we quantify the impact of epidemic parameters on the capacity of the uniformly mixing reduced model to predict key epidemic outcomes. 

Finally, we consider density-dependent population processes in general. We establish a many-to-one formula which reduces the typical lineage of a sampled individual to a time-inhomogeneous spinal process. In addition, we use a coupling argument to quantify the large population convergence of a spinal process.

**Keywords:** Epidemic processes, random graphs, two levels of mixing, model reduction.

**Jury** 
- Anne de Bouard, Directrice de Recherche, École polytechnique (President)
- Tom Britton, Professor, Stockholm University (Referee) 
- Laurent Massoulié, Directeur de recherche, INRIA (Referee)
- Simon Cauchemez, Directeur de recherche, Institut Pasteur (Examiner)
- Clémentine Prieur, Professeur, Université Grenoble Alpes
- Viet Chi Tran, Professeur, Université Gustave Eiffel (Examiner)
- Vincent Bansaye, Professeur, École polytechnique (Supervisor)



