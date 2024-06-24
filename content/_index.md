---
title: "TL Test page"
type: landing
sections:
  
  - block: hero
    content:
      title: Tegla Loroupe Peace Foundation
    # banner:
    # image: tlhome.jpg
    # caption: 'Image credit: Olympics Committee'
    content:
      title: 4
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: tlhome.jpg
          image_darken: 0.9
          image_size: cover
          image_position: left
          image_parallax: true
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
     # image:
      #  placement: 3
     #   caption: 'Photo by '
    #    focal_point: 'Center'
    #    preview_only: false
    #    alt_text: Ambassador Tegla Loroupe
    #    filename: tlhome.jpg
     # text: 
     #   <br>     
     #   Ambassador Tegla Loroupe has led the World Olympics Refugee Team to two Olympics.

  - block: collection
    id: 3-latest
    content:
      title: Updating in 2024: Latest News
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
  
  - block: markdown
    content:
      title: 4
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: tlhome.jpg
          filters:
            brightness: 1
            parallax: false
            position: center
            size: cover
            text_color_light: true
        spacing:
        padding: ['20px', '0', '20px', '0']
        css_class: fullscreen
  
  - block: markdown
    content:
      title: 5
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet all the teams →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title: 5.5
      subtitle:
      text: |
        {{% cta cta_link="./pages/" cta_text="Meet some of the team →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title: Tegla Loroupe Peace Foundation
      text: >- 
        <br>
        ## The Tegla Loroupe Peace Foundation creates peace initiatives in East African pastoralist conflict areas.

        Since its founding in 2003 by **World Champion Tegla Loroupe**, thousands of athletes have trained and competed in Peace Races held in conflict areas in Kenya, in Uganda, and in other conflict areas.
        <hl>
        Since 2015, hundreds of refugee athletes from South Sudan, Congo, Ethiopia, Somalia and other countries have trained at the [Tegla Loroupe International Olympic Refugee Training Camp in Ngong, Kenya](http://bit.ly/37Y0sc3), just  to the west of Nairobi.

        In 2016, Ambassador Tegla Loroupe led the International Refugee Olympic team to Rio, where five of the Ngong Training Camp athletes competed.

        In 2021, Ambassador Tegla Loroupe led the International Refugee Olympic team to Tokyo.

        Tegla Loroupe describes who we are:  an organization dedicated to athletes who compete for themselves, for their families, for their societies, and for peace, honesty and justice among all peoples.

      subtitle: Peace Through Sports Again
  #    image:
  #    placement: 2
   #   focal_point: right
    design:
      columns: '1'
      background:
        image: 
          filename: tlhome.jpg
          image_darken: 0.9
          image_size: cover
          image_position: left
          image_parallax: true
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  - block: markdown
    content:
      title: 7
      subtitle: 'We are at 7'
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: 'tl.young.girl.jpg'
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen 

  - block: skills
    content:
      title: 8. Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: collection
    id: posts
    content:
      title: 9 Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'  

  - block: portfolio
    id: projects
    content:
      title: 10. Projects
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false 

  - block: markdown
    content:
      title: 11. Gallery
      subtitle: ''
      text: |-
        {{< gallery album="gallery" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: 12. Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: 13. Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: collection
    id: talks
    content:
      title: 14. Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact

  - block: tag_cloud
    content:
      title: 15. Popular Topics
    design:
      columns: '2'

  - block: markdown
    content:
      title: Copied this from website 
      subtitle: My subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: people
    content:
      title: Our Athletes, Our Leaders, Our Students
      user_groups:
        - Staff
        - Board
        - Management
        - Visitors
        - Alumni
        - Athletes
        - South Sudan
        - Ngong Training Camp
        - Kapenguria Academy
        - Olympics
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true 
    
---

