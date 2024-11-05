This is a simple way to host a blog, making use of the GitHub GraphQL API to retrieve updated blog entries.

I will be attempting to use front matter in markdown files.  For instance, if you open a post file, the front matter could look like this:

```markdown

---
title: "My First Blog Post"
date: "2024-11-05"
tags: ["intro", "personal"]
---
```

This block would be placed at the very top, and the post content would follow. When the file is fetched from GitHub, the idea would be that metadata could be parsed separately from the post body, so it can be used for things like showing the date and tags on the blog or generating a list of posts with titles.