---
title: Photoshop Showcase
publishDate: 2023-05-15
img: /assets/photoshop-cover.jpg
description: |
  A scrollable gallery of Photoshop projects, including photo edits, composites, and posters.
tags:
  - Photoshop
  - Gallery
  - Digital Art
---

> A small selection of images I have created for work, and for fun.

---

### Photoshop Gallery

<div class="masonry-gallery">

  <!-- <img src="/assets/photoshop/ld-primus-flag.jpg" alt="Poster Design"> -->
  <img src="/assets/photoshop/PedalOutMainLogoBlack.jpg" alt="Wide Composite">
  <img src="/assets/photoshop/PedalOutMainLogoWhite.jpg" alt="Wide Composite">
  <img src="/assets/photoshop/IMG_20190701_133049.jpg" alt="Wide Composite">
    <img src="/assets/photoshop/ld-ski-club-blue.jpg" alt="Wide Composite">
  <img src="/assets/photoshop/ld-ski-club-green.jpg" alt="Wide Composite">
  <img src="/assets/photoshop/ld-fjall-flag.jpg" alt="Tall Retouch">
  <img src="/assets/photoshop/accenture-banner.jpg" alt="Banner Design" class="full-width">
</div>
</div>

<style>
.masonry-gallery {
  column-count: 2;
  column-gap: 1rem;
}

.masonry-gallery img {
  width: 100%;
  margin-bottom: 1rem;
  break-inside: avoid;
  border-radius: 6px;
}

/* Make full-width images break out of the columns */
.full-width {
  width: 100%;
  display: block;
  break-inside: avoid;
  margin-bottom: 1.5rem;
  grid-column: 1 / -1;
  /* Override column layout */
  column-span: all;
}
</style>
---