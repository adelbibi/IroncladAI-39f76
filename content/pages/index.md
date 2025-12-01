---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: AI Safety & Agent Security Consulting for Modern Enterprises
      color: text-dark
      type: TitleBlock
    subtitle: Oxford-trained experts helping teams deploy AI safely and confidently.
    text: >
      Ironclad AI is a consultancy specializing in AI safety, agent security, and
      responsible deployment. Backed by Oxford research, SoftServe delivery experience,
      contributions to major AI-related legal cases, and funding from UK AISI, Amazon,
      and Google, we help teams ship AI systems securely and efficiently.
    media:
      # url: /images/main-herto.svg
      url: /images/ironcladai-logo.jpg
      altText: AI safety and agent consulting visual
      elementId: ''
      type: ImageBlock
      styles:
        self:
          alignItems: center
          padding: [pt-16, pl-16, pb-16, pr-16]
    elementId: ''
    variant: three-col-grid
    colors: bg-dark-fg-dark
    styles:
      self:
        padding: [pb-16, pt-16, pl-16, pr-16]
        justifyContent: center
      subtitle:
        textAlign: center

  - type: FeaturedItemsSection
    title:
      text: Consulting Services
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: High-impact advisory and engineering support for AI and agentic systems.
    variant: four-col-grid
  
    # Explicit grid template (helps themes that ignore variant)
    styles:
      self:
        padding: [pt-16, pl-8, pb-16, pr-8]
        justifyContent: center
        display: grid
        gridTemplateColumns: repeat(4, minmax(220px, 1fr))
        gridGap: 16px
      subtitle:
        textAlign: center
    items:
      - type: FeaturedItem
        title: Threat Modeling
        tagline: Understand your risks
        subtitle: Identify vulnerabilities early.
        text: >
          Risk mapping across LLMs, agents, and pipelines with clear mitigation steps.
        image:
          url: /images/Gemini_Generated_Image_2_cropped.png
          altText: Threat modeling illustration
          type: ImageBlock
          styles:
            self:
              borderRadius: x-large
        colors: bg-light-fg-dark
        styles:
          self:
            padding: [pt-8, pl-8, pb-8, pr-8]
            borderRadius: large

      - type: FeaturedItem
        title: Adversarial Red Teaming
        tagline: Test for real failures
        subtitle: Expose gaps before attackers do.
        text: >
          Adversarial testing of LLMs and agents supported by award-winning research.
        image:
          url: /images/Gemini_Generated_Image_3_cropped.png
          altText: Red teaming visualization
          type: ImageBlock
          styles:
            self:
              borderRadius: x-large
        colors: bg-light-fg-dark
        styles:
          self:
            padding: [pt-8, pl-8, pb-8, pr-8]
            borderRadius: large

      - type: FeaturedItem
        title: AI R&D Advisory
        tagline: Stay cutting-edge
        subtitle: SOTA research & internal guidance.
        text: >
          Expert direction for teams building advanced AI and agentic capabilities.
        image:
          url: /images/Gemini_Generated_Image_1_cropped.png
          altText: Research advisory illustration
          type: ImageBlock
          styles:
            self:
              borderRadius: x-large
        colors: bg-light-fg-dark
        styles:
          self:
            padding: [pt-8, pl-8, pb-8, pr-8]
            borderRadius: large

      - type: FeaturedItem
        title: AI Strategy & Deployment
        tagline: Accelerate delivery
        subtitle: From idea to production.
        text: >
          Hands-on guidance to help teams deploy AI responsibly and efficiently.
        image:
          url: /images/Gemini_Generated_Image_4_cropped.png
          altText: Deployment illustration
          type: ImageBlock
          styles:
            self:
              borderRadius: x-large
        colors: bg-light-fg-dark
        styles:
          self:
            padding: [pt-8, pl-8, pb-8, pr-8]
            borderRadius: large

    colors: bg-neutral-fg-dark

  - type: ImageGallerySection
    subtitle: Acknowledged by
    images:
      - url: /images/oxford-logo.svg
        altText: University of Oxford
        type: ImageBlock
        styles:
          self:
            height: 56px
            width: auto
            margin: [mr-24]
      - url: /images/amazon-logo.svg
        altText: Amazon
        type: ImageBlock
        styles:
          self:
            height: 56px
            width: auto
            margin: [mr-24]
      - url: /images/google-logo.svg
        altText: Google
        type: ImageBlock
        styles:
          self:
            height: 56px
            width: auto
            margin: [mr-24]
      - url: /images/softserve-logo.png
        altText: SoftServe
        type: ImageBlock
        styles:
          self:
            height: 56px
            width: auto
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        padding: [pt-16, pb-16]
      subtitle:
        textAlign: center

  - type: GenericSection
    elementId: contact
    title:
      text: Contact Us
      color: text-dark
      type: TitleBlock
    subtitle: Get expert support for your AI systems.
    text: >
      Tell us what you're building — we’ll help you move forward safely.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: How can we help?
          width: full
          type: TextareaFormControl
      elementId: contact-form
      colors: bg-light-fg-dark
      styles:
        self:
          padding: [pt-6, pb-6, pl-6, pr-6]
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        style: primary
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-neutral-fg-dark

seo:
  metaTitle: AI Safety & Agent Consulting — Ironclad AI
  metaDescription: AI safety and agent security consulting backed by Oxford research, SoftServe delivery, UK AISI funding, and awards from Amazon and Google.
  socialImage: /images/main-hero.jpg
  type: Seo

type: PageLayout
---
