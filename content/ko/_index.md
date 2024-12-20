---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 학교재학증명서
        url: uploads/학교재학증명서.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.png
          filters:
            brightness: 0.6
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: "📚 주요 기획서들"
      text: 현재 개발이 예정된 기획서들 입니다.
      filters:
        folders:
          - planning
    design:
      view: article-grid
      fill_image: true
      columns: 3
  - block: collection
    content:
      title: "📚 주요 프로젝트"
      text: 현재 개발 중이거나 개발이 완료된 프로젝트들입니다.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: true
      columns: 3

  # - block: collection
  #   id: papers
  #   content:
  #     title: 완료된 프로젝트들
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ""
  #     text: ""
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    content:
      title: 현재 웹사이트의 깃허브 주소
      text: |-
        해당 웹사이트의 깃허브 주소로 이동!!

        <a class="github-button bg-cyan-500" href="https://github.com/mandlake/mandlake.github.io" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star Hmandlake/mandlake.github.io on GitHub">Star</a>

    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-cyan-500"
        css_style: "background-color: rgb(6 182 212);"
---
