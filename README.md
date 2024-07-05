# Rust-Edu Bookmark Organization

Trying out ideas for organizing the 100+ bookmarks for rust-edu.org

## Idea 1: TOML & Tags

Resource bookmarks will be discrete `.toml` files, stored in a `bookmarks/` directory (or, if preferred, in a single big `bookmarks.toml`.) Each bookmark will be a table with the following fields:

```TOML
name = "Bookmark Name"
url = "https://example.com"
description = "A short description of the bookmark."
tags = ["tag1", "tag2", "tag3"]
```

JSON as an alternative to doing this with TOML. But I kinda ❤️ TOML.
