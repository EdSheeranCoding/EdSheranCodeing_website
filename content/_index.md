---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: static/uploads/resume.pdf
      # here is where you would have the button to your blog
    design:
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
