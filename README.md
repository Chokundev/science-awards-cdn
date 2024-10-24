
# SCIENCE-AWARDS 2025 CDN

This repository hosts the **Content Delivery Network (CDN)** for the **SCIENCE-AWARDS 2025** contest management system. The CDN is designed to efficiently serve static assets and resources, ensuring fast and reliable content delivery for the SCIENCE-AWARDS 2025 system.

## Purpose

The CDN enhances the performance of the SCIENCE-AWARDS 2025 system by providing:
- Fast and distributed access to static assets (e.g., images, stylesheets, and JavaScript files)
- Reduced server load by caching assets closer to users
- Improved scalability and availability

## Technology Stack

This CDN is built using **Cloudflare Pages**, taking advantage of Cloudflare's global edge network to deliver content efficiently.

## Usage Instructions

To integrate the CDN into the SCIENCE-AWARDS 2025 system, link the static resources hosted on the CDN using the following format:

https://sci-awards.site/ < path-to-resource >


 Replace `<path-to-resource>` with the specific file path (e.g., images, CSS, JS) within the CDN.

Example usage in an HTML file:
```html
<link rel="stylesheet" href="https://sci-awards.site/science-awards-2025/styles/main.css">
<script src="https://sci-awards.site/scripts/app.js"></script``
