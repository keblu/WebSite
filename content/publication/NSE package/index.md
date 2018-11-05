+++
title = "NSE: Computation of Numerical Standard Errors in R"

date = 2017-08-06T00:00:00
draft = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["David Ardia","Keven Bluteau"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Journal of Open Source Software, Vol. 10, No. 2, 2017"
publication_short = "Journal of Open Source Software, Vol. 10, No. 2, 2017"

# Abstract and optional shortened version.
abstract = "NSE is an R package for computing the numerical standard error (NSE), an estimate of the standard deviation of a simulation result if the simulation experiment were to be repeated many times. The package provides a set of wrappers around several R packages, which give access to more than thirty estimators, including batch means estimators (Geyer (1992 Section 3.2), initial sequence estimators (Geyer (1992 Equation 3.3), spectrum at zero estimators (Heidelberger and Welch (1981),Flegal and Jones (2010), heteroskedasticity and autocorrelation consistent (HAC) kernel estimators (Newey and West (1987), Andrews (1991), Andrews and Monahan (1992), Newey and West (1994), Hirukawa (2010), and bootstrap estimators Politis and Romano (1992), Politis and Romano (1994), Politis and White (2004)."


# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["NSE"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["bootstrap", "HAC kernel" ," numerical standard error (NSE)", "Monte Carlo","spectral density", "R software"]

# Links (optional). 
url_pdf = "http://joss.theoj.org/papers/10.21105/joss.00172"
url_custom = [
{name = "SSRN", url = "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2911549"},
{name = "CRAN", url = "https://CRAN.R-project.org/package=nse"},
{name = "Github", url = "https://github.com/keblu/nse"}]


# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.21105/joss.00172"
# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

