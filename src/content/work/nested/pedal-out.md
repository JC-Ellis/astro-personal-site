---
title: PedalOut
publishDate: 2025-04-15 00:00:00
img: /assets/PedalOut.jpg
img_alt: A mobile app displaying cycling trails and group rides, with a scenic trail map in the background
description: |
  A social cycling app that helps riders discover trails, share events, and connect with others — built with React Native and MongoDB.
tags:
  - React Native
  - TypeScript
  - Express
  - MongoDB
  - Supabase
---
> From casual rides to mountain trails — PedalOut brings cyclists together, one ride at a time.

PedalOut is a cross-platform social cycling app built with **React Native**, **TypeScript**, **Express**, and **MongoDB**. It helps users discover local rides, create their own, and connect with other cyclists in their area — whether you're just out for a spin or looking to join a group event.

New users can sign up or log in via **Supabase Auth**, and after onboarding, they’re taken to their profile to upload an avatar and set preferences. The home page displays upcoming rides, each showing ride info, location imagery, and participant counts. A map view also allows users to browse events by location.

---

### Key Features

- Post your own rides by pinning a location on the map and entering event details
- Browse interactive maps with real-time ride markers (powered by **Google Maps API**)
- Join rides, view participants, and follow other users
- Set events to **private**, viewable only by people you follow

---

### Community and Chat

The **Connections** page helps users manage their followers and followings, making it easier to share and discover rides in trusted circles. Messaging is handled through a real-time **chat** feature, backed by **MongoDB**, where each message is stored as a document and grouped by chat ID. Conversations update instantly and allow users to message friends or group participants without delay.

---

### Tech Highlights

- RESTful backend with full CRUD functionality
- Authentication and user syncing via **Supabase**
- Real-time chat built on **MongoDB** with efficient document structure
- Fully tested front end using **Jest**
- Designed with accessibility and mobile-first UX in mind

<div style="padding:56.25% 0 0 0;position:relative;">
  <iframe 
    src="https://player.vimeo.com/video/1080116140?h=a1233010a7&badge=0&autopause=0&player_id=0&app_id=58479"
    frameborder="0" 
    allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media"
    style="position:absolute;top:0;left:0;width:100%;height:100%;"
    title="PedalOut Presentation"
  ></iframe>
</div>