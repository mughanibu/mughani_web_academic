+++
title = "Deep Learning-Based Sinogram Completion for Low-Dose CT"
date = 2018-06-10
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Muhammad Usman Ghani", "W. Clem Karl"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Image, Video, and Multidimensional Signal Processing Workshop (IVMSP)*, IEEE."
publication_short = "In *IVMSP*"

# Abstract and optional shortened version.
abstract = "Patient radiation dose associated with $X$-ray CT is a significant concern in the medical community. One of the ways to reduce patient dose is to acquire projection data at fewer angles. Using conventional reconstruction methods with such sparsely sampled data introduces severe streaking artifacts in the reconstructions, that reduces their diagnostic utility. Conventional methods in this domain have focused on postprocessing the artifact-filled images or the use of model-based inversion techniques with image-domain priors. In this work, we examine the potential of a deep-learning-based method to construct a mapping from the observed, sparsely sampled, CT projection data to a set of densely sampled projection estimates directly in the original projection domain. We cast the problem as one of sinogram in-painting and focus on completing the projection data prior to reconstructing the images. As compared to existing work, we focus on “correcting” the data rather than the subsequent images and avoid costly iterative tomographic inversion. Our initial results on a simulated dataset demonstrate the potential effectiveness of this new approach in suppressing artifacts."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Computed Tomography", "Low-dose ,"Sparse-view", "Convolutional neural networks" , "Deep learning"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/abstract/document/8448403"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1109/IVMSPW.2018.8448403"

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Deep Low-Dose CT"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
