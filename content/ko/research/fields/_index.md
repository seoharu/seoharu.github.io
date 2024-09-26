<!-- ---
# Page title
title: My page
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: section-2
    content:
      title: Research Fields
      subtitle: 여러 연구 주제 분야
      text: ""
      # Display content from the `content/post/` folder
      filters:
        folders:
          - research/fields
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: list
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
--- -->

<!-- ---
title: Research Fiedls

# Listing view
view: community/custom_list

# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: 'research.jpg'
--- -->

---
banner:
  caption: ''
  image: 'research.jpg'
---