+++

widget = "pages"  # Use the Pages widget
headless = true  # This file represents a page section.

title="Publication"

# ... Put Your Section Options Here (title etc.) ...

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "post"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 5
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false
    exclude_past = false
    exclude_future = false
    
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2

  [[item]]
  organization = "Coursera"
  organization_url = "https://www.coursera.org"
  title = "Neural Networks and Deep Learning"
  url = ""
  certificate_url = "https://www.coursera.org"
  date_start = "2018-10-01"
  date_end = ""
  description = ""

[[item]]
  organization = "edX"
  organization_url = "https://www.edx.org"
  title = "Blockchain Fundamentals"
  url = "https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals"
  certificate_url = "https://www.edx.org"
  date_start = "2018-03-01"
  date_end = ""
  description = "Formulated informed blockchain models, hypotheses, and use cases."
  
[[item]]
  organization = "DataCamp"
  organization_url = "https://www.datacamp.com"
  title = "Object-Oriented Programming in R: S3 and R6 Course"
  url = ""
  certificate_url = "https://www.datacamp.com"
  date_start = "2017-07-01"
  date_end = "2017-12-21"
  description = ""
+++