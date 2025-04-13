---
# Leave the homepage title empty to use the site title
title:
date: 2024-12-12
type: landing

sections:
  - block: hero
    content:
      title: Welcome to the <br> Neurosarcoidosis dataset.
      image:
        filename: manuscript_scheme.png
      text:

  - block: markdown
    content:
      title:
      text: |
        This is the corresponding website to the publication [Leukocyte profiles in blood and CSF distinguish neurosarcoidosis from multiple sclerosis](https://doi.org/10.1016/j.jneuroim.2020.577171) 
        by Heming et. al, *Journal of Neuroimmunmology* 2020. We analyzed flow cytometry of blood and CSF from patinets suffering from neurosarcoidosis and multiple sclerosis.

  - block: collection
    id: datasets
    content:
      title: Dataset
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: datasets
    design:
      view: showcase
      columns: '1'
      flip_alt_rows: false

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        If you have any questions, please contact us via [mheming.com](https://www.mheming.com).
---
