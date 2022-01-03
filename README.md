# Jekyll Starter

> Starting point for Jekyll sites using [Tailwind CSS](https://tailwindcss.com/)
and [Alpine.js](https://github.com/alpinejs/alpine/).

[![Open in Visual Studio Code](https://img.shields.io/badge/Open%20in-Visal%20Studio%20Code-blue?style=for-the-badge&logo=visualstudiocode)](https://open.vscode.dev/0fflineDocs/CloudEndpointBlog)
[![Use this template](https://img.shields.io/badge/template-Generate-green?style=for-the-badge)](https://github.com/tabs-not-spaces/jekyll-starter/generate)
[![Unlicense](https://img.shields.io/badge/license-Unlicense-blue?style=for-the-badge)](https://choosealicense.com/licenses/unlicense/)

## Getting Started

Working from an assumption that you are building on a Windows device with WSL2 + Docker installed, everything you need to get started building your Jekyll site with Tailwind CSS is included in this template.

- Click the "Open in Visual Studio Code" button in this readme. 
- Select "Clone repo in container volume".
- Follow the bouncing ball.
- Once the container is built & the repo is cloned:
    - open the command pallette (ctrl+shift+P), search for "Run Task".
    - Run the included "Jekyll: Build Dev" task.

You should now have everything built and running that you need to start working on your site 🚀

## What's Included

This is not a Jekyll theme. It's a starting point to create a website using
[Jekyll](https://jekyllrb.com/), [Tailwind CSS](https://tailwindcss.com/), and
[Alpine.js](https://github.com/alpinejs/alpine/). The layout includes almost
nothing, allowing you to start building right away instead of having to remove
code you won't use.

If you want to start creating posts and pages, we've included the
[Jekyll::Compose](https://github.com/jekyll/jekyll-compose) plugin.

    bundle exec jekyll page "My New Page"
    bundle exec jekyll post "My New Post"

## Deploying

Includes configuration for deploying to [GitHub Pages](https://pages.github.com/) (via GitHub Actions).
