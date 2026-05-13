# Yuxin Lu Academic Homepage

This repository contains a one-page AcademicPages/Jekyll homepage with content generated from Yuxin Lu's local `MyBlog` project.

## Main Files

- `_config.yml`: site title, sidebar profile, contact links, GitHub, Google Scholar, and avatar.
- `_pages/about.md`: the homepage content.
- `_pages/cv.md`: CV download page.
- `images/yuxin-lu-profile.webp`: profile photo copied from `MyBlog/public/profile.webp`.
- `files/YuxinLu_CV.pdf`: CV copied from `MyBlog/public/YuxinLu_CV.pdf`.

## Deploy

Push this folder to your `lyx-JuneSnow.github.io` repository and enable GitHub Pages. The homepage content is generated from `_pages/about.md`.

## Local Preview

Use a modern Ruby environment with Jekyll/GitHub Pages support:

```bash
bundle install
bundle exec jekyll serve
```
