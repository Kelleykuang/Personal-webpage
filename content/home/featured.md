---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured
active: true
# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 80

title: Publications
subtitle: ""

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Filter on criteria
  filters:
    author: ""
    category: ""
    publication_type: ""
    tag: ""
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 3
item:
- title: "EarphoneTrack: Involving Earphones into the Ecosystem of Acoustic Motion Tracking"
  # Authors
  # If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
  # and it will be replaced with their full name and linked to their profile.
  authors:
  - Gaoshuai Cao
  - admin
  - Jie Xiong
  - Panlong Yang
  - Yubo Yan
  - Hao Zhou
  - Xiang-Yang Li

  # Author notes (optional)
  author_notes:
  - "Equal contribution"
  - "Equal contribution"

  date: "2020-11-01T00:00:00Z"
  doi: "10.1145/3384419.3430730"

  # Schedule page publish date (NOT publication's date).
  publishDate: "2017-01-01T00:00:00Z"

  # Publication type.
  # Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
  # 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
  # 7 = Thesis; 8 = Patent
  publication_types: ["1"]

  # Publication name and optional abbreviated publication name.
  publication: In Proceedings of the 18th Conference on Embedded Networked Sensor Systems
  publication_short: In [***SenSys'20***](http://sensys.acm.org/2020/)

  abstract: Acoustic motion tracking is an exciting new research area with promising progress in the last few years. Due to the inherent low propagation speed in the air, acoustic signals have the unique advantage of fine sensing granularity compared to RF signals. Speakers and microphones nowadays are pervasively available in devices surrounding us, such as smartphones and voice-controlled smart speakers. Though promising, one fundamental issue hindering the adoption of acoustic-based motion tracking is that the positions of microphones and speakers inside a device are fixed, which greatly limits the flexibility of acoustic motion tracking. In this work, we propose a new modality of acoustic motion tracking using earphones. Earphone-based  tracking mitigates the constraints associated with traditional smartphone-based tracking. With novel designs and comprehensive experiments, we show earphone-based motion tracking can achieve a great flexibility and a high accuracy at the same time. We believe this is an important step towards "earable" sensing. 

  # Summary. An optional shortened abstract.
  summary: In this work, we propose a new modality of acoustic motion tracking using earphones. With novel designs and comprehensive experiments, we show earphone-based motion tracking can achieve a great flexibility and a high accuracy at the same time.

  tags: []

  # Display this page in the Featured widget?
  featured: true

  # Custom links (uncomment lines below)
  # links:
  # - name: Custom Link
  #   url: http://example.org

  url_pdf: ''
  url_code: ''
  url_dataset: ''
  url_poster: ''
  url_project: ''
  url_slides: 'presentation-long-EarphoneTrack.pptx'
  url_source: ''
  url_video: 'https://www.youtube.com/watch?v=OVNR4WdZKl4'
---
