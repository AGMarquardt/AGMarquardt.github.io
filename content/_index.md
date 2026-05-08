---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: hero
    content:
      title: |
        Marquardt
        Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Marquardt Lab** works at the interface of RNA Biology, Gene Expression and Epigenomics research. We are based at the Institute of Biochemistry and Biology, University of Potsdam, Germany, and the Department of Biology, Lund University, Lund, Sweden.
        
        **We are hiring!** Open positions for PhD students and Postdocs coming soon.
  
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
      title: Upcoming Events
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - event
      offset: 0
      order: asc
      page_type: event
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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
      title: Funding & Support
      subtitle: ''
      text: |
        We gratefully acknowledge support from our funders:

        **ERC** | **Novo Nordisk Foundation** | **DFG** | **Carlsberg Foundation** | **EMBO** | **Alexander von Humboldt Foundation** | **Carl Tesdorpf Stiftelsen** | **Vetenskapsrådet** | **Danmarks Frie Forskningsfond**

        {{< figure src="funding-wordcloud.png" >}}
    design:
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
