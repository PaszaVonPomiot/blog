# Blog info

## Techonology
- Static Site Generator: Hugo
- Theme: hugo-coder

## Setup
```
choco install hugo-extended -confirm
git clone https://github.com/PaszaVonPomiot/blog.git
cd blog/strefadysk
git submodule add https://github.com/luizdepra/hugo-coder.git themes/hugo-coder  # link theme
git submodule add https://github.com/PaszaVonPomiot/paszavonpomiot.github.io.git public  # link hosting page
hugo server  # test on localhost
hugo  # write to ./public
cd public
git add/commit/push
```

## TODO
- landing page with list of posts, about page separate
- post thumbnails auto-read by templates and displayed in post and on index page
- landing page with branding
- post categories/tags
- read time in polish
- better datetime

