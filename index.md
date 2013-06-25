---
layout: page
title: Geting Started
---
{% include JB/setup %}


## environment setup
    [rvm install](http://ruby-china.org/wiki/rvm-guide)
    gem install jekyll    

## workflow
    git clone git@github.com:XingCloud/HMitosis.git
    git checkout -b gh-pages origin/gh-pages
    
    create page:
    rake post title="Hello World"

    create post:
    rake page name="hbase/hfile-inside.md" [title="HFile的格式？"]
    
    edit:
    ...

    deploy on local to preview:
    jekyll --server 3000
    http://localhost:3000/

    deploy to github:
    git commit -am "add hfile page"
    git push
