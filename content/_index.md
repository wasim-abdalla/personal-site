---
title: Home
sections:
- type: heroblock
  template: heroblock
  title: Hi, I'm Wasim Abdalla. Welcome to my personal site!
  section_id: hero
  component: hero_block.html
  content: Let's make things.
- type: portfolioblock
  template: portfolioblock
  title: Recent Work
  section_id: latest-projects
  component: portfolio_block.html
  subtitle: What I've been up to
  layout_style: mosaic
  num_projects_displayed: 6
  view_all_text: View All
  view_all_url: portfolio/index.html
- type: postsblock
  template: postsblock
  title: Latest from my Blog
  section_id: latest-posts
  component: posts_block.html
  subtitle: Pixels & Threads
  num_posts_displayed: 2
  actions:
  - label: View Blog
    url: blog/index.html
- type: contactblock
  template: contactblock
  title: Contact Us
  section_id: contact
  component: contact_block.html
  subtitle: An optional subtitle of the section
layout: home
menu:
  main:
    weight: 1

---
