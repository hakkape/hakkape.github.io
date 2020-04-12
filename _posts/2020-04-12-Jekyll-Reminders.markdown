---
layout: single
title:  "Jekyll Reminders"
date:   2020-04-12 12:16:00 +0200
categories: Jekyll
---

### New posts

Create file like "_posts/YYYY-MM-DD-title.markdown", add front matter:

```yaml
---
layout: single
title: "What the title should be"
date: 2020-04-12 12:16:00 +0200
categories: SomeCategory
---
```

### New pages

Create file like "_pages/title.markdown", add front matter:

```yaml
---
layout: single
title: TITLE
permalink: /TITLE/
---
```

### Adding pages to masthead

Add entry in "_data/navigation.yml"

### Adding header image to page

Add following to front matter:

```yaml
header:
  image: /assets/images/headermain.jpg
```

For landing page header, doe the same in the index.html front matter