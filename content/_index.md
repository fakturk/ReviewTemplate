---
title: 'Professional Book Review Templates'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"
  color:
    primary: "purple"  # Main brand color
   # dark: false        # Light mode by default

sections:
  # ========== HERO SECTION ==========
  - block: hero
    content:
      title: "Stunning Canva Templates for Book Lovers"
      subtitle: "Create professional reviews 10x faster"
      text: |
        **500+ Bookstagrammers & Bloggers Love These Templates**  
        Perfect for ARCs, reviews, and author features
      primary_action:
        text: "Browse Templates"
        url: "/templates"
        icon: shopping-cart
      secondary_action:
        text: "Free Sample"
        url: "/freebie"
    design:
      background:
        color: "primary"  # Uses your primary purple
        image:
         # filename: "book-hero-bg.jpg"  # Add textured background
          filename: book-hero-bg.jpg
          filters:
            brightness: 0.5
            contrast: 1.2
            saturation: 0.8
            blur: 2
      css_class:
        text-center
        [background:rgba(0,0,0,0.3)]
        dark:[background:rgba(0,0,0,0.5)]
        px-8 py-4 rounded-xl
        [text-shadow:_0_2px_4px_rgba(0,0,0,0.7)]
        dark:[text-shadow:none]

  # ========== GENRE SHOWCASE ==========
  - block: features
    id: genres
    content:
      title: "Template Collections by Genre"
      subtitle: "Each designed with genre-specific aesthetics"
      items:
        - name: "Fantasy"
          icon: wand-sparkles
          description: "Emerald green + gold | Medieval fonts | Parchment textures"
          image: "fantasy-preview.jpg"
          button:
            text: "View Pack"
            url: "/templates/fantasy"
        - name: "Romance"
          icon: heart
          description: "Blush pink + rose gold | Elegant scripts | Floral accents"
          image: "romance-preview.jpg"
        - name: "Sci-Fi"
          icon: robot
          description: "Neon blue/purple | Futuristic fonts | Galaxy backgrounds"
          image: "scifi-preview.jpg"
    design:
      columns: "3"  # 3-column grid
      card_style: "hover:shadow-lg"  # Lift on hover

  # ========== TESTIMONIALS ==========
  - block: testimonials
    content:
      title: "Loved by Book Creators"
      items:
        - name: "TheBookishDragon"
          role: "Bookstagrammer (50K followers)"
          image: "testimonial-1.jpg"
          text: "My engagement doubled with these templates - worth every penny!"
        - name: "LitReviewBlog"
          role: "Book Blogger"
          image: "testimonial2.jpg"
          text: "Saves me 5+ hours per week designing review graphics"
    design:
      columns: "2"

  # ========== GUMROAD INTEGRATION ==========
  - block: cta-card
    content:
      title: "Ready to Elevate Your Reviews?"
      text: "Instant download after purchase"
      button:
        text: "Shop on Gumroad"
        url: "https://reviewtemplate.gumroad.com/"
        icon: shopping-bag
    design:
      card:
        css_class: "bg-gradient-to-r from-purple-600 to-pink-500"
---
