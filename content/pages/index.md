---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-f
    backgroundWidth: full
    title: 'Work communication, the remote way'
    text: >
      One platform, one comunity, getting to the bottom line of everything
      emloyment.  Figure out your benefits, practice for interviews, get
      mentored, help peers, get helped in return.
    actions:
      - type: Button
        label: Get Started
        url: 'https://www.stackbit.com/'
        style: secondary
        elementId: hero-main-button
    feature:
      type: ImageBlock
      url: /images/header Image.png
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: screen
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-0
          - pb-0
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-12
          - mb-4
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-6
      text:
        textAlign: left
        margin:
          - mt-0
          - mb-8
      actions:
        justifyContent: flex-start
  - elementId: ''
    variant: variant-b
    colors: colors-a
    backgroundWidth: full
    title: Here are som brands
    subtitle: and thier logos
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hilary-ouse.json
      - content/data/team/hugh-saturation.json
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-32
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
  - elementId: ''
    colors: colors-a
    backgroundWidth: inset
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
    title: Where did everyone go?
    subtitle: >-
      Learn how to get yourself, your team, and your organization connected,
      inspired, and efficient in a WFH environment. 
    actions:
      - type: Button
        label: Watch video
        url: /
        style: secondary
        elementId: hero-main-button
      - type: Button
        label: Learn more
        url: /
        style: link
        icon: arrowRight
        showIcon: true
    feature:
      type: ImageBlock
      url: /images/Rectangle 2419.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: full
        margin:
          - mt-32
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: flex-end
        flexDirection: row
        borderColor: border-neutral
        borderRadius: xx-large
        borderWidth: 3
        borderStyle: solid
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-12
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mt-12
          - mb-12
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    variant: variant-c
    colors: colors-a
    backgroundWidth: full
    title: Remote doesn’t mean alone
    subtitle: >-
      Latest blog post on how companies use Chatto.io to bring community and
      efficiency to their workflow
    actions:
      - type: Button
        label: View all
        url: /
        style: secondary
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-32
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPostsSection
  - elementId: ''
    colors: colors-f
    backgroundWidth: full
    backgroundImage:
      altText: lorem-ipsum
      caption: lorem-ipsum
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
      url: /images/BAckground.png
    title: A platform that allows everyone the most productive version of themselves
    text: >
      ## Share WIP, comment on each other’s work, approve what’s ready to go,
      ship together
    actions:
      - type: Button
        label: Learn More
        url: /
        style: secondary
        icon: arrowRight
        showIcon: true
    feature:
      type: ImageBlock
      url: /images/Center image.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-36
          - mb-36
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-12
          - mb-12
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      text:
        textAlign: left
        margin:
          - mb-12
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: ContactSection
    colors: colors-a
    backgroundWidth: full
    title: Join our club
    text: >-
      We will notify you every time a shipment is heading to your neighborhood,
      and you could immediatly let us know if you want in or not.
    feature:
      type: ImageBlock
      url: /images/Demo image-b28d3dbc.png
      altText: Fisherman holding lobster
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-36
          - mb-36
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: flex-start
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
---
