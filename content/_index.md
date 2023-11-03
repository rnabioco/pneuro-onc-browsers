---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: portfolio
    id: atlases
    content:
      title: Atlases
      sort_by: 'Date'
      sort_ascending: true
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: andrew.donson@cuanschutz.edu
      appointment_url: 
      address:
        street: Dept of Pediatrics and The Morgan Adams Foundation Pediatric Brain Tumor Research Program
        city: Aurora
        region: CO
        postcode: '80045'
        country: United States
        country_code: US
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      contact_links:
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
