---
type: PageLayout
title: Home
colors: colors-b
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Andrew Brown's Portfolio
    subtitle: >-
      I'm a senior at Michigan studying CS and entrepreneurship. I've been into
      building stuff since high school—started tinkering with code and never
      stopped. These days I'm focused on product and engineering, working on
      everything from AI features to workflow automation. Outside of tech, I'm
      trying to get better at golf (emphasis on trying) and spending time with
      friends.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: false
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/crypto-proj.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-one.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-four.md
      - content/pages/projects/project-five.md
      - content/pages/projects/betahedging.md
      - content/pages/projects/mhacks2024.md
      - content/pages/projects/saaswebapp.md
      - content/pages/projects/movie-suggester.md
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
---
