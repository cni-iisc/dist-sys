---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: |
        Distributed Systems Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        The research work in the lab focuses on performance analysis and design of large-scale distributed systems connected by a network such as Internet, data center networks, public and private cloud. Our current focus is on computation over such networks, e.g. a heterogeneous compute cluster for large AI models. Some of our recent works are on the design of messaging protocol design for large scale computations over such networked compute nodes, scheduling of computation jobs over these clusters, pricing of the networked compute nodes for revenue maximization, and configuration and resource management to achieve optimal energy performance tradeoffs.

        **Motivated students who are interested in pursuing a PhD working on cutting-edge research problems in the theory and systems research for communication networks may email us.**
  
  - block: collection
    content:
      title: Latest News
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
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
