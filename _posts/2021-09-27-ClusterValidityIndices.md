---
title: ClusterValidityIndices.jl
subtitle: A Julia package for batch and incremental cluster validity indices.
layout: single
date: 2021-09-27
categories: ["projects"]
tags: [
    "Julia",
    "CVI"
]
summary: ClusterValidityIndices.jl is registered as an official JuliaHub.

header:
    # image: "/assets/posts/cvi-header.png"
    teaser: "/assets/posts/cvi-header.png"
    caption: "The ClusterValidityIndices.jl package."

# featured: true
# # profile: true
# # commentable: true
# # share: true

# # Link this post with a project
# projects: ["ClusterValidityIndices.jl"]

# links:
#   - icon_pack: fab
#     icon: osi
#     name: Publication
#     url: '/publication/joss-cvi'

# header:
#     # image: headers/bubbles-wide.jpg
#     image: path.jpg
#     caption: "Cluster validation."

# # Featured image
# # To use, place an image named `featured.jpg/png` in your page's folder.
# # Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# # Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# # Set `preview_only` to `true` to just use the image for thumbnails.
# image:
#   placement: 1
#   caption: "ART Module Architecture"
#   # focal_point: "Center"
#   focal_point: "TopLeft"
#   preview_only: false
---

![ClusterValidityIndices.jl](/assets/posts/cvi-header.png)

[`ClusterValidityIndices.jl`](https://github.com/AP6YC/ClusterValidityIndices.jl) is a registered [JuliaHub](https://juliahub.com/ui/Packages/ClusterValidityIndices/Z19r6) package for incremental and batch Cluster Validity Indices (CVI/ICVI).
These algorithms are used for determining the quality and performance of a clustering algorithm in the absence of a supervisory signal.
The contributions of the project are represented as a [paper](https://joss.theoj.org/papers/10.21105/joss.03527) in the Journal of Open Source Software (JOSS).

The `ClusterValidityIndices.jl` package is represented in the following locations:

- [GitHub](https://github.com/AP6YC/ClusterValidityIndices.jl)
- [Documentation](https://ap6yc.github.io/ClusterValidityIndices.jl/dev/)
- [JuliaHub](https://juliahub.com/ui/Packages/ClusterValidityIndices/Z19r6)
- [The Journal of Open Source Software (JOSS)](https://joss.theoj.org/papers/10.21105/joss.03527)

The project can be cited with the following BibTex entry:

```bibtex
@article{Petrenko2022,
  doi = {10.21105/joss.03527},
  url = {https://doi.org/10.21105/joss.03527},
  year = {2022},
  publisher = {The Open Journal},
  volume = {7},
  number = {79},
  pages = {3527},
  author = {Sasha Petrenko and Donald C. Wunsch},
  title = {ClusterValidityIndices.jl: Batch and Incremental Metrics for Unsupervised Learning},
  journal = {Journal of Open Source Software}
}
```
