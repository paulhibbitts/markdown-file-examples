---
title: 'Tools for Open Course Design'
url: 'http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design'
markdown: 'http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design.md'
date: '2026-10-26'
description: "By the end of this section you will be able to Compare Grav and Docsify-based approaches for open course content Explain how Git Sync enables version-controlled course content Embed a Grav or Docsify page into an LMS using a URL parameter Building open course content doesn't require learning a n…"
taxonomy:
  archives_month:
    - oct_2026
  archives_year:
    - '2026'
---

Section 2

# Tools for Open Course Design

On this page

- [A Full Site with Grav](#a-full-site-with-grav)
- [A Single Page with Docsify-This](#a-single-page-with-docsif)
- [Showing Only the Content](#showing-only-the-content)

> [!TIP]
> 
> **By the end of this section you will be able to**
> 
> - Compare Grav and Docsify-based approaches for open course content
> - Explain how Git Sync enables version-controlled course content
> - Embed a Grav or Docsify page into an LMS using a URL parameter

Building open course content doesn't require learning a new authoring system from scratch. The tools covered here are designed to layer on top of workflows you likely already use.

## A Full Site with Grav

[Grav](https://getgrav.org) is a flat-file CMS – all content is stored as Markdown files, with no database required. Pair it with the Git Sync plugin and every save is automatically committed to a GitHub or Codeberg repository.

**Best for:** Educators who want a full-featured course or reader site with an Admin Panel, multi-contributor support, and rich theming.

## A Single Page with Docsify-This

[Docsify-This](https://docsify-this.net) takes a different approach – paste the URL of any public Markdown file and get back a styled, shareable web page instantly. No account, no configuration, nothing to install.

**Best for:** Sharing a single page or section instantly, or publishing a reading without setting up a full site.

## Showing Only the Content

Both Grav and Docsify support clean content-only views via a URL parameter:

```
https://yoursite.com/open-education-essentials/what-is-open-education?chromeless=true
```

Adding `?chromeless=true` removes the header, sidebar, and footer – leaving only the content for embedding in an iFrame inside Canvas, Moodle, or Brightspace.

> [!IMPORTANT]
> 
> **Tip for Canvas Users**
> 
> Use the **External Tool** option (not iFrame embed) for the best accessibility and mobile experience when embedding open content in Canvas.

This work by [Your Name](#) is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

- Open Education
- [What is Open Education?](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/what-is-open-education)
- [Tools for Open Course Design](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design)
- - [A Full Site with Grav](#a-full-site-with-grav)
    - [A Single Page with Docsify-This](#a-single-page-with-docsif)
    - [Showing Only the Content](#showing-only-the-content)
- [LMS Embedding](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design/lms-embedding)
- [Git Sync – Version-Controlled Content](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design/git-sync)
- [Docsify-This for Instant Publishing](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design/docsify-this)

- [Getting Started with Open Authoring](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/getting-started-with-open-authoring)
- Publishing with This Site
- [Growing Your Guide](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/growing-your-guide)

Want to see these tools in a real course? [Try the Open Course Hub demo](https://demo.hibbittsdesign.org/grav-open-course-hub/)

---

## Navigation

- Parent: [Open Education Essentials](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/index.md)
- Previous: [What is Open Education?](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/what-is-open-education.md)
- Next: [Getting Started with Open Authoring](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/getting-started-with-open-authoring.md)
- Children:
  - [LMS Embedding](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design/lms-embedding.md)
  - [Git Sync – Version-Controlled Content](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design/git-sync.md)
  - [Docsify-This for Instant Publishing](http://localhost:8080/_TESTS/grav-skeleton-open-publishing-space/open-education-essentials/tools-for-open-course-design/docsify-this.md)
