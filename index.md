---
layout: page
title: Geting Start
---
{% include JB/setup %}


## environment setup
    [rvm install](http://ruby-china.org/wiki/rvm-guide)
    gem install jekyll    

## usage
    git clone git@github.com:XingCloud/HMitosis.git
    git checkout -b gh-pages origin/gh-pages
    
    create page:
    rake post title="Hello World"

    create post:
    rake page name="HMitosis/hbase-locks.md"
    
    local deploy:
    jekyll --server 3000
    http://localhost:3000/

