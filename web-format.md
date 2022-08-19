---
layout: post
title: Format
description: Lorem ipsum dolor est
image: assets/images/pic11.jpg
nav-menu: false
show_tile: false
---
# Web format for FourierIndustries Home Page

This document seeks to outline the format of the website, how the website content should be laid out, etc.

## Hierarchy

- index.md: Root index page, should contain key links to different parts of the site. Additionally contains some 
    - products.md: Products showcase, based on the landing.md template
    - newsroom.md: Latest news from the company, based on the all_posts.md template
    - documentation.md -> redirect to the knowledge base https://knowledge.fourier.industries
    - support.md -> redirect to the support page https://fourierindustries.atlassian.net/servicedesk/customer/portals
    - NOTE: the elements above have a custom property called `tile-number`, which specifies the order they should be shown in the tile menu, instead of being sorted alphabetically

- elements.md: Internal page. Used for sourcing UI elements
- generic.md: Internal page. Used as a template for blog posts
- landing.md: Internal page. Used for showcasing a portfolio-style page mostly made with custom HTML instead of markdown

## Menu

Hamburger menu on the top right will be present on all pages except the index page. 
