
# MentalHealthable

_A curated feed for modern mental health news._

---
## Aims

### Core Goal

MentalHealthable will use NewsAPI V2 to feature curated feeds of content related to mental health technology. 

### Stretch Goals

Utilizing the Youtube, Instagram, and Inspirational Quotes APIs to intersperse unique and original content into the curated feeds. Including advanced alt tags and descriptions for accessibility readers. 

---
## Methods

### Overview

Avoiding personal bias in keyword selection, MentalHealthable will create a main feed by selecting multiple keywords related to positive mental health content ("mindfulness", "inspiration", "mood", etc.) and technology ("apps", "wearables", "trackers").

### Structure

Each related term will use "OR" tags, while categories will be concatenated with an "AND" tag, as allowed by the advanced NewsAPI query, casting a wide net across news media and blogging websites. Certain anti-keywords will be utilized to avoid including any potentially triggering or graphic content. Category specific pages ("tech", "apps", etc.) would contain content specific to each category; a search function would be available to reference all queries in the NewsAPI database.

### Terms

* Health
  * Mental Health
  * Mental Healthcare
  * Wellbeing
  * Wellness
  * Mindfullness
  * Meditation
  * Fitness
  * Nutrition
* Technology
  * Technology
  * Tech
  * Apps
  * 

---
## Design

### Overview

Immersive, fullwidth design with minimal content and backgrounds, a simple color palette, and advanced CSS elements such as box shadows, parralax scrolling, and interactice hover elements– putting the API-called content front and center, allowing for a pleasant viewing experience– will be utilized. For accessibility needs, MentalHealthable will feature full WCAG 2.0 compliance and restricted use of low-contrast or low-transparency elements.

### Pages

* index.html
* style.css
* script.js

### Mockups

Desktop Mockup:
<img src="/mockup-desktop.png">

Tablet Mockup:
<img src="/mockup-tablet.png">

Mobile Mockup:
<img src="/mobile-mockup.png">

---
## Domain

https://www.mentalhealthable.surge.sh

---

# Task List

<!-- * Add search function to bottom of page -->
<!-- * Add js hide until scroll for footer menu -->
<!-- * Add responsiveness– headers, menus, img div heights, etc. -->
<!-- * Consider additional API, insprational quotes? -->

## Improvements 

* The API is unfortunately quite limited in relevant news stories; an "editor's picks" curated section that would have a hard coded, relevant stories would have been helpful.

## Unsolved Problems

* After committing to Surge, the live mobile site breaks the images. 

  * (Coded as background images with 100vh, and multiple attempts at changing up the media queries, I believe each image is trying to take a height of the full HTML body– which on mobile with extensive scroll, makes each background image massive, to the point that 3 pixels take up the width of the screen.)

  * On the same surge site, while viewing through Chrome Inspect or just a resized Chrome window, this doesn't happen.