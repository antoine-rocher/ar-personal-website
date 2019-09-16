---
title: Home
sections:
  - component: HeroBlock
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
    section_id: hero
    type: heroblock
  - actions:
      - label: About me
        url: /about
      - label: View resume
        url: 'https://drive.google.com/open?id=16RrxPbFS0dsgiACWSk-fJKwgAsPIrtq0'
    component: ContentBlock
    content: >-
      Hello, my name is Antoine Rocher and I am a recent graduate in
      Astrophysique from the Master of Astrophysics of Unversité Claude Bernard
      Lyon 1.


      I am very interested in science in general and especially physics and
      astrophysics. I also like sport (I played basketball during 8 years in
      competion) and I was very involved in the university student associations.
    section_id: about
    title: About
    type: contentblock
  - actions:
      - label: View Posts
        url: blog/index.html
    component: PostsBlock
    num_posts_displayed: 4
    section_id: recent-posts
    title: Recent Posts
    type: postsblock
menus:
  main:
    title: Home
    weight: 1
template: home
---

