# Setup
## Install jekyll
https://jekyllrb.com/docs/installation/
```
cd /path/to/folder
gem update
gem install jekyll bundler
jekyll -v
```

## Start local dev server
```
bundle exec jekyll serve --host 0.0.0.0 --livereload
```

## deploy
simply push to github
```
git push origin master
```