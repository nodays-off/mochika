# Mochika Website - Image Placement Guide

This document shows exactly where each of the 40+ Gemini-generated images goes in the website HTML.

---

## HOME PAGE IMAGES

### 1. Hero Section (Top of page)
**Image: `home_hero_main.webp` (2400×1350px)**
- **Location**: Replace the placeholder inside `<section id="home" class="hero">`
- **HTML to find**:
```html
<div class="placeholder-image hero-image">
    [Home Hero Image: Person with Nicaraguan features holding coffee mug...]
</div>
```
- **Replace with**:
```html
<img src="images/home_hero_main.webp" alt="A person with Nicaraguan features holding a mug of coffee on a lush hillside farm at sunrise with misty green hills and distant volcanoes" class="hero-image">
```

---

### 2. Why Mochika Section (4 icon images, 800×800px each)
**Location**: Inside `<section class="why-mochika">`

#### Icon 1: Family-grown
- **HTML to find**:
```html
<div class="why-icon">
    <div class="placeholder-image" style="border-radius: 20px;">🏡</div>
</div>
```
- **Replace with**:
```html
<div class="why-icon">
    <img src="images/icon_family_grown.webp" alt="Icon of a small farmhouse on coffee-covered hills with a coffee plant">
</div>
```

#### Icon 2: Ethical & Fair
- **HTML to find**: Second `.why-icon` with 🤝 emoji
- **Replace with**:
```html
<div class="why-icon">
    <img src="images/icon_ethical_fair.webp" alt="Icon of a handshake above a coffee branch symbolizing fair relationships">
</div>
```

#### Icon 3: Accessible Ritual
- **HTML to find**: Third `.why-icon` with ☕ emoji
- **Replace with**:
```html
<div class="why-icon">
    <img src="images/icon_everyday_ritual.webp" alt="Icon of a steaming coffee mug on a small table representing daily coffee rituals">
</div>
```

#### Icon 4: Sustainability
- **HTML to find**: Fourth `.why-icon` with 🌱 emoji
- **Replace with**:
```html
<div class="why-icon">
    <img src="images/icon_sustainability.webp" alt="Icon of a coffee plant sprouting from soil with circular arrows representing sustainability">
</div>
```

---

### 3. Featured Coffee Section (3 product images, 1200×1500px each)

#### Product 1: Matagalpa Sunrise
- **HTML to find**:
```html
<div class="coffee-image">
    <div class="placeholder-image" style="height: 100%;">
        [Product Image: Matagalpa Sunrise Coffee Bag]
    </div>
</div>
```
- **Replace with**:
```html
<div class="coffee-image">
    <img src="images/product_matagalpa_sunrise.webp" alt="Matagalpa Sunrise coffee bag standing on a cream linen surface with roasted beans scattered around it">
</div>
```

#### Product 2: Golden Hour
- **HTML to find**: Second `.coffee-image` placeholder
- **Replace with**:
```html
<div class="coffee-image">
    <img src="images/product_golden_hour.webp" alt="Golden Hour medium roast coffee bag displayed with coffee beans on neutral background">
</div>
```

#### Product 3: Volcano Night
- **HTML to find**: Third `.coffee-image` placeholder
- **Replace with**:
```html
<div class="coffee-image">
    <img src="images/product_volcano_night.webp" alt="Volcano Night dark roast coffee bag displayed upright with a few coffee beans at its base on a neutral background">
</div>
```

---

### 4. Story Teaser Section (1 image, 1600×1067px)
**Location**: Inside `<section id="story" class="story-teaser">`

- **HTML to find**:
```html
<div class="story-image">
    <div class="placeholder-image" style="height: 100%;">
        [Story Image: Nicaraguan family on coffee farm]
    </div>
</div>
```
- **Replace with**:
```html
<div class="story-image">
    <img src="images/home_story_teaser.webp" alt="Nicaraguan family standing together among coffee plants on their farm smiling softly at the camera">
</div>
```

---

## CURRENT WEBSITE IMAGE COUNT: 9 images on home page

---

## ADDITIONAL PAGES (Not yet built in HTML, but images are ready)

### OUR STORY PAGE IMAGES (8 images)
1. **story_hero.webp** (2400×1000px) - Story page hero banner
2. **story_timeline_vintage_farmer.webp** (1400×1050px) - Historical timeline
3. **story_timeline_seedling.webp** (1400×1050px) - Planting seedling
4. **story_timeline_roastery.webp** (1600×1067px) - Modern roastery
5. **story_team_portrait_1.webp** (1200×1500px) - Founder portrait
6. **story_team_portrait_2.webp** (1200×1500px) - Farm manager portrait
7. **story_team_portrait_3.webp** (1200×1500px) - Team member portrait
8. **story_nicaragua_map.webp** (1600×1600px) - Nicaragua map illustration

### COFFEE/PRODUCTS PAGE IMAGES (6 images)
1. **coffee_hero_lineup.webp** (2400×1350px) - All coffee bags in a row
2. **coffee_product_lifestyle_kitchen.webp** (1600×1067px) - Coffee on kitchen table
3. **coffee_product_lifestyle_pourover.webp** (1600×1067px) - Pour-over brewing
4. **coffee_brew_guide.webp** (1600×1200px) - Brewing equipment top-down

*Plus 3 detailed product images for each coffee if you want individual product pages*

### WHOLESALE PAGE IMAGES (3 images)
1. **wholesale_hero.webp** (2400×1350px) - Two people cupping coffee
2. **wholesale_warehouse_sacks.webp** (1600×1067px) - Coffee sacks on pallets
3. **wholesale_cupping_closeup.webp** (1600×1200px) - Cupping bowls

### IMPACT PAGE IMAGES (3 images)
1. **impact_hero_family.webp** (2400×1350px) - Multi-generational farmers
2. **impact_sustainability_bag_leaf.webp** (1600×1200px) - Sustainable packaging
3. **impact_community_education.webp** (1600×1067px) - Community education

### BLOG/LEARN PAGE IMAGES (3 images)
1. **blog_cover_brew_better.webp** (1920×1080px) - Brewing setup
2. **blog_cover_nicaragua_special.webp** (1920×1080px) - Coffee cherries
3. **blog_cover_cherry_to_cup.webp** (1920×1080px) - Journey composite

### CONTACT PAGE IMAGE (1 image)
1. **contact_side_image.webp** (1600×1200px) - Coffee mug with laptop

### FAQ PAGE IMAGE (1 image)
1. **faq_header_icon.webp** (800×800px) - Speech bubble with mug

---

## SUMMARY BY PRIORITY

### **Priority 1: Currently in HTML (9 images)**
✅ These go in the current website you have:
- 1 Hero background image
- 4 Why Mochika icons
- 3 Product images (coffee bags)
- 1 Story teaser family photo

### **Priority 2: Home Page Enhancement (Optional, 2 images)**
These can be added to enhance the current home page:
- Impact teaser image (hands exchanging beans)
- Newsletter section image (optional)

### **Priority 3: Additional Pages (29 images)**
These are for when you build out the other pages:
- Our Story page: 8 images
- Coffee page: 6 images
- Wholesale page: 3 images
- Impact page: 3 images
- Blog page: 3 images
- Contact page: 1 image
- FAQ page: 1 image

---

## FILE STRUCTURE RECOMMENDATION

Create this folder structure:
```
mochika-website/
├── index.html (your main website file)
├── images/
│   ├── home/
│   │   ├── hero_main.webp
│   │   ├── icon_family_grown.webp
│   │   ├── icon_ethical_fair.webp
│   │   ├── icon_everyday_ritual.webp
│   │   ├── icon_sustainability.webp
│   │   ├── product_matagalpa_sunrise.webp
│   │   ├── product_golden_hour.webp
│   │   ├── product_volcano_night.webp
│   │   └── story_teaser.webp
│   ├── story/
│   │   └── [8 story page images]
│   ├── products/
│   │   └── [6 product page images]
│   ├── wholesale/
│   │   └── [3 wholesale images]
│   ├── impact/
│   │   └── [3 impact images]
│   ├── blog/
│   │   └── [3 blog cover images]
│   └── contact/
│       └── [contact page images]
└── css/
    └── styles.css (optional if you want separate CSS)
```

---

## QUICK START CHECKLIST

For the **current home page** to look complete, you need these 9 images from Gemini:

- [ ] `home_hero_main.webp` - Hero background
- [ ] `icon_family_grown.webp` - Why Mochika icon 1
- [ ] `icon_ethical_fair.webp` - Why Mochika icon 2
- [ ] `icon_everyday_ritual.webp` - Why Mochika icon 3
- [ ] `icon_sustainability.webp` - Why Mochika icon 4
- [ ] `product_matagalpa_sunrise.webp` - Coffee product 1
- [ ] `product_golden_hour.webp` - Coffee product 2
- [ ] `product_volcano_night.webp` - Coffee product 3
- [ ] `home_story_teaser.webp` - Family story image

Once you have these 9 images generated, search for the placeholder text in the HTML and replace with the `<img>` tags as shown above.

---

## NOTES

- All placeholder divs are marked with `class="placeholder-image"` for easy finding
- Use browser "Find" (Ctrl+F / Cmd+F) to search for "placeholder-image" to locate each one
- The current website focuses on the HOME page - other pages can be built later
- WebP format is preferred for web optimization, with JPEG fallbacks if needed
