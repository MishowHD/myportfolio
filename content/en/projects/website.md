+++
title = "Personal Website & Workflow"
date = "2025-10-20"
draft = false
+++

My personal website is built using **Hugo**, the **Hugo Coder** theme, and an automated deployment workflow designed for speed, simplicity, and long-term maintainability.  
I chose an open-source static site generator to keep full control over my content, ensure long-term stability, and avoid dependencies on external platforms or databases.

---

## Tech Stack

- Hugo (static site generator)  
- Hugo Coder theme  
- Markdown-based content  
- Multilingual EN/IT setup  
- GitHub repository for version control  
- GitHub Pages for automated builds  
- Cloudflare for CDN, HTTPS, and caching  
- Custom domain with DNSSEC enabled  

---

## Why I Chose Hugo (and Static Site Generators)

I selected **Hugo** because it is:

- extremely fast (builds in milliseconds)  
- open-source and supported by a strong community  
- secure by design (no server-side code, no database)  
- flexible thanks to themes, templates, and shortcodes  
- ideal for long-term maintainability  

This makes it a perfect solution for a personal portfolio.

---

## Deployment Workflow

1. Write content in Markdown  
2. Commit changes to GitHub  
3. GitHub Pages builds the site using Hugo  
4. Cloudflare distributes the static files globally  

This workflow offers:

- automatic builds  
- atomic deployments  
- global CDN caching  
- HTTPS by default  
- zero downtime  

---

## Security and Performance

- Fully static (no backend, no database)  
- Served over HTTPS  
- DNSSEC enabled  
- Globally cached via Cloudflare  
- No tracking or analytics scripts  

---

## Why This Architecture

- Full version control  
- Easy updates  
- Multilingual support  
- Zero backend maintenance  
- Clean and maintainable structure  
- Strong security and long-term stability  
- Open-source tools and full content ownership  

This website is both my personal portfolio and an engineering project where I experiment with static-site generation, deployment automation, and clean architectural design.
