+++
title = "Markov-Switching GARCH Models in R: The MSGARCH Package"

date = 2018-05-31T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["David Ardia","Keven Bluteau","Kris Boudt", "Leopoldo Catania", "Denis-Alexandre Trottier"]

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
publication = "Journal of Statistical Software, Forthcoming"
publication_short = "Journal of Statistical Software, Forthcoming"

# Abstract and optional shortened version.
abstract = "We describe the package MSGARCH, which implements Markov-switching GARCH models in R with efficient C object-oriented programming. Markov-switching GARCH models have become popular methods to account for regime changes in the conditional variance dynamics of time series. The package MSGARCH allows the user to perform simulations as well as Maximum Likelihood and MCMC/Bayesian estimations of a very large class of Markov-switching GARCH-type models. The package also provides methods to make single-step and multi-step ahead forecasts of the complete conditional density of the variable of interest. Risk management tools to estimate conditional volatility, Value-at-Risk and Expected Shortfall are also available. We illustrate the broad functionality of the MSGARCH package using exchange rate and stock market return data."


# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["MSGARCH"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["GARCH", "MSGARCH" ,"Markov-switching", "conditional volatility","forecasting", "R software"]

# Links (optional).
url_pdf = "https://www.jstatsoft.org/article/view/v091i04"
url_custom = [
{name = "SSRN", url = "https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2845809"},
{name = "CRAN", url = "https://cran.r-project.org/package=MSGARCH"},
{name = "Github", url = "https://github.com/keblu/MSGARCH"}]


# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.2139/ssrn.2845809"
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

