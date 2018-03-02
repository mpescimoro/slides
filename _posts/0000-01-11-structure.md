## Structure

* _includes: partials that can be mixed and matched by your layouts and posts to facilitate reuse {% fragment %}
* _layouts: templates that wrap posts {% fragment %}
* _posts: content goes HERE {% fragment %}
* _sass: Syntactically Awesome StyleSheets {% fragment %}
* _config.yml: stores configuration data. {% fragment %}
* _site: where the generated site will be placed (by default)

---

## Structure

A basic Jekyll site usually looks something like this:

```bash
├── _config.yml
├── _data
|   └── members.yml
├── _drafts
|   ├── begin-with-the-crazy-ideas.md
|   └── on-simplicity-in-technology.md
├── _includes
|   ├── footer.html
|   └── header.html
├── _layouts
|   ├── default.html
|   └── post.html
├── _posts
|   ├── 2009-04-26-barcamp-boston-4-roundup.md
|   └── 2014-08-31-a-day-to-remember.md
├── _sass
|   ├── _base.scss
|   └── _layout.scss
├── _site
├── .jekyll-metadata
└── index.html
```
