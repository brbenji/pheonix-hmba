---
title: Online Musician Essentials
layout: collection
permalink: /essentials/
collection: essentials
entries_layout: list
---
Collection can be created by following the instructions in /minimal-mistakes/docs/_docs/13-collection.md

Goes like this:
- Add yaml info in config.yml telling it about your collection.
- Optionally create defaults for your yaml Front Matter, still within config.yml.
- Create a < collection >.md file inside the new _pages folder.
- Create a < _collection > folder. This is where you can place your posts. Each new file will show up in this page with the layout: collection, which can be found through the permalink /essentials/s.

Not sure how to link this back to this page from home. or index. or root. entries_layout: #grid, #list. Also removed classes: wide from the front matter, it was extending the entries all the way across the $large page.