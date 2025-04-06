# RossGallery SEO Metadata
This repository contains structured SEO metadata used for dynamic SEO injection on [RossGallery.com](https://www.rossgallery.com). It powers per-path Open Graph, Twitter Card, and SEO descriptions for category and subcategory pages.
---
## 📄 File
- `seoData.json`: A structured JSON object mapping URL paths to their respective SEO metadata (title, description, canonical URL, and Open Graph image).
---
## 🧠 Purpose
The SEO metadata is loaded dynamically on Squarespace using a JavaScript script injected via the site's header. This improves page-specific indexing, social sharing cards, and search engine optimization.
---
## 🔧 Usage
This JSON file is fetched by the global SEO script in Squarespace using:
```javascript
fetch("https://your-github-raw-link/seoData.json")
