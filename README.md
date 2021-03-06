# high Clean Jekyll theme [![Build Status](https://travis-ci.org/nandomoreirame/high.svg?branch=master)](https://travis-ci.org/oracy/high)

- [x] Clean layout
- [x] Resposive layout
- [x] Preprocessor SASS
- [x] CSS minified
- [x] Pagination
- [x] Syntax highlight
- [x] Author config
- [x] Comments with Disqus
- [ ] Search posts
- [ ] Share posts

---

### Start in 4 steps

1. Download or clone repo `git clone git@github.com:Oracy/high.git`
2. Enter the folder: `cd high/`
3. Install Ruby gems: `bundle install`
4. Start Jekyll server: `bundle exec jekyll serve`

Access, [localhost:4000/high](http://localhost:4000/high)

### Deploy in Github pages in 2 steps

1. Change the variables `GITHUB_REPONAME` and `GITHUB_REPO_BRANCH` in `Rakefile`
2. Run `rake` or `rake publish` for build and publish on Github

---

### Using Rake tasks

- Create a new page: `rake page name="contact.md"`
- Create a new post: `rake post title="TITLE OF THE POST"`

---
