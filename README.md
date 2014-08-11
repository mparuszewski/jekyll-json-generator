jekyll-json-generator
=====================

Simple Jekyll generator that generates json files from posts.

# JSON Generator for Jekyll

Jekyll plugin for generating an json from post content.

If you want to load your posts with AJAX or load just load them as JSON and render view then JSON Generator for Jekyll is for you.

## Installation

In your Jekyll site source root directory, create or open a `_plugins` directory. Paste `json_generator.rb` there.

## Usage

JSON Generator will generate JSON files with `/json/` prefix on each post (in `_posts` directory). For example if you had post with route http://yourname.github.io/categories/news/2014-08-11-my-first-post your json format of this post will be http://yourname.github.io/json/categories/news/2014-08-11-my-first-post/index.json.

Each post has structure:

```json
{
    "title": "Post title",
    "created_at": "2014-08-10 20:50:00 UTC",
    "author": "Your name",
    "content": "Your content"
}
```
