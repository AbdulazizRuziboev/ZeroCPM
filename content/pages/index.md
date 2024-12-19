---
title: ZeroCPM - Bosh sahifa
slug: /
sections:
  - type: GenericSection
    title:
      text: ZeroSHOP
      color: text-dark
      type: TitleBlock
    subtitle: GameGuardian uchun
    text: |+
      > Bu saytda o'zingizga kerakli ma'lumot  topa olasiz degan umidaman ! 

    actions:
      - label: Boshlash
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Kuzatish
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/wp6543280-car-drifting-4k-desktop-wallpapers (1).jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ZERO CPM
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Ma'lumotlar
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: "Bu pullik manbadir!\_ Ya'ni siz ko'proq imkoniyatlarga ega bo'lasiz"
    items:
      - type: FeaturedItem
        title: O'rnatish
        subtitle: 4$ evaziga
        text: >
          Sizga GameGuardian o'rnatish o'rgatiladi va qo'shimcha scriptlar ham
          beriladi! Eng arzon narxlarda albatta!
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/ggic.png
          styles:
            self:
              borderRadius: x-large
      - title: Scriptlar
        subtitle: 1~3 $ evaziga
        text: >
          Sizga scriptlarni ham taklif etamiz! Bu bilan ishingiz juda ham
          osonlashadi !
        image:
          url: /images/tools-icon.png
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Scarlet
        subtitle: 15$ evaziga
        text: >
          Bu bilan istalgan turdagi pulli narsalarni ochishingiz mumkin! Bu
          faqat IOS qurilmalari uchun ishlaydi
        image:
          url: /images/sc.png
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions: []
    badge:
      label: Game guardian
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: CarouselSection
    title: null
    subtitle: Bu loyiha egasi
    items:
      - title: Creator ZeroSHOP
        tagline: Ro'ziboyev Abdulaziz
        subtitle: 'Uzbekistan, Fergana region, Kuvasay city'
        text: |
          GG Tutorials master

          GG Script maker
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Hamkor
        tagline: A'zamjon Umarov
        subtitle: 'Uzbekistan, Kokand city'
        text: |
          Frontent-dev

          GG hacker
        image:
          url: /images/person-placeholder-light.png
          altText: John Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Habar qoldirish
      color: text-dark
      type: TitleBlock
    subtitle: 24-soat ichida javob qaytadi!
    text: >
      Agar 24 soat ichida javob qaytmasa @RuziboevAbdulaziz Telegram havolasi
      bilan menga bog'lanib ko'ring!
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Ismingiz
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email manzilingiz
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Sizning xabaringiz
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Yuborish
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Bog'lanish
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
