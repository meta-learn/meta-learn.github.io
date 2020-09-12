## Guidelines for future years

Please maintain the nested structure of the website repository. In particular, each year of the workshop should have its own subfolder that contains an index page `index.md` as well as a `slides` folder and a `papers` folder. The landing pages from previous years (_i.e._, the existing subfolders `/201[0-9]`) as well as the global config files should remain unmodified in future years. However, future landing pages accessible at `metalearning.ml` may introduce a new webpage style as long as they maintain a visible link to all previous years of the workshop.

### Instructions for refreshing the website

To make the website ready for the year `20XX`:

1.  Create a folder `20XX`.
2.  Create a Markdown file at `20XX/index.md` with the webpage content. Feel free to copy the template from the previous year `20XX - 1`, adding a link to `(20XX - 1)/index.md` under `#Past Workshops`. Ensure that the header of `20XX/index.md` includes 

```
---
title: Workshop on Meta-Learning (MetaLearn 20XX)
description: "@NIPS 20XX <br> DATE <br> LOCATION"
permalink: /20XX/index.html
weight: -1
redirect_from: /201XX/
---
```
3. Create subdirectories within `20XX` (_e.g._, `20XX/papers` or `20XX/slides`) to contain media specific to the current year's workshop.
4. Modify the root landing page at `index.html` to redirect to `http://metalearning.ml/20XX/`.
