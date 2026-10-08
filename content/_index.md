---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      market: On the 2026-2027 Job Market
      text:
    design:
      css_class: dark
      spacing:
        padding: ['28px', '0', '32px', '0']
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.8
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Welcome!'
      subtitle: ''
      text: |-
        I am an empirical economist and currently a postdoc at the Kellogg School of Management at Northwestern University. I work on Development Economics, Political Economy, and Economic History.
    
        My job market paper studies how son preference spreads across groups and persists across generations. My other work examines how information and economic change shape political preferences and economic behavior.
    
        Prior to Northwestern University, I received my PhD in Economics in 2025 and MA in Economics from the Toulouse School of Economics. I also hold a BBA in Economics from The Chinese University of Hong Kong, Shenzhen.
        

    design:
      columns: '1'
      css_class: homepage-intro
      spacing:
        padding: ['44px', '0', '36px', '0']
  - block: homepage-publication
    id: job-market-paper
    content:
      title: 'Job Market Paper'
      publication: 'publication/son preference'
    design:
      columns: '1'
      css_class: homepage-jmp
      spacing:
        padding: ['0', '0', '80px', '0']
---
