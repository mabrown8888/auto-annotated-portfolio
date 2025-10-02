---
type: PageLayout
title: Store
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: Apps & Services
    subtitle: Check out what I've built
    text: ''
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderColor: border-complementary
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: left
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        title: Tabster.AI
        subtitle: AI-Powered Bill Splitting App
        text: >
          Split bills effortlessly with AI-powered receipt scanning. Automatically
          itemize bills, share with friends, and settle up instantly. Download now
          on the App Store!
        featuredImage:
          type: ImageBlock
          url: /images/tabster-logo.png
          altText: Tabster.AI Logo
        actions:
          - type: Button
            label: Download on App Store
            url: 'https://apps.apple.com/us/app/tabster-ai/id6737703202'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
        styles:
          self:
            textAlign: center
            padding:
              - pt-4
              - pl-4
              - pb-4
              - pr-4
    columns: 1
    spacingX: 16
    spacingY: 16
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: DividerSection
    styles:
      self:
        width: narrow
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: Coming Soon
    subtitle: More projects and services on the way
    text: >
      Stay tuned for more software and digital products!
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
addTitleSuffix: true
colors: colors-b
---
