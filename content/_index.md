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
        url: uploads/cv.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: null
      biography:
        # Customize the style of your biography text
        style: |
          text-align: justify; 
          font-size: 0.8em; 
          padding-left: 1rem; 
          padding-right: 1rem;
          
          @media only screen and (max-width: 600px) {
            padding-left: 2rem;
            padding-right: 2rem;
          }
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  # - block: skills
  #   content:
  #     # title: Skills & Hobbies
  #     title: Skills
  #     username: admin
  # - block: awards
  #   content:
  #     title: Awards
  #     username: admin

---
