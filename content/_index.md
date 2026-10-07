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
      market: 2026–27 Economics Job Market Candidate
      text:
    design:
      css_class: dark
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
    
        My job market paper studies the cultural transmission of son preference across groups and across generations. My research also studies the interplay between economics, politics, and cultures.
    
        Prior to Northwestern University, I received my PhD in Economics in 2025 and MA in Economics from the Toulouse School of Economics. I also hold a BBA in Economics from the Chinese University of Hong Kong in Shenzhen.
        

    design:
      columns: '1'
      css_class: homepage-intro
  - block: markdown
    content:
      title: 'Job Market Paper'
      text: |-
        ### [The Transmission of Son Preference](/publication/son-preference/)

        [Paper](/upload/papers/Son_Preference.pdf) · [Abstract](/publication/son-preference/)

        I study how son preference spreads across groups and persists across generations. I exploit the quasi-random settlement of mainland Chinese migrants in Taiwan, measuring their son preference through ancestor worship in their places of origin. After the Legalization of Abortion in 1985, local parents exposed to migrants with stronger son preference became more likely to select for sons and, when they had no son, to continue childbearing. Among migrants' descendants, son preference persists through paternal lineage and migrant communities.
    design:
      columns: '1'
      css_class: homepage-jmp
      spacing:
        padding: ['0', '0', '80px', '0']
---
