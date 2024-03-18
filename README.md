# Essential Kit
This is source for the website at http://essentialkit.org
<br />

This is a template and some instructions for running Github Pages with the minima theme. This repo has the minimum pieces for a blog using Jekyll and Github Pages:

* Frontpage that includes your last blog posts: `_pages/frontpage.md`
* Custom collection type `_extensions`
* Archive for all your posts: `_pages/archive.md`
* About page: `_pages/about.md`
* Minimum 404 page: `_pages/404.md`
* Minimum metadata in the `_config.yml`
* Example CSS change inside `assets/main.scss`
* Custom footer template `_includes/footer.html`

### Reference

- [Base template](https://github.com/jsanz/gh-pages-minima-starter)
- [Theme: Jekyll Minima](https://github.com/jekyll/minima)
- [Jekyll](https://jekyllrb.com/)
- [Working with Github Pages](https://help.github.com/en/github/working-with-github-pages)


### Development

1. Install dependencies
```
bundle install
```

2. Start local server with live-reload
```
bundle exec jekyll serve
```


# TODO
- Calculator demo is not working since the switch out of iframes.
- The demo needs to be invoked directly, without a window.PostMessage (which is also better, avoids triggering extension)
- It's hard to access the object across scripts, so I assigned it to the window in ContentScript.
