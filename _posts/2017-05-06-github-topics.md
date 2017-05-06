---
layout: post
title:  "github-topics"
date:   2017-05-06
excerpt: "node module for getting list of topics of a repository on github"
project: true
tag:
- github-topics
- topics
- github-scrapper
- nodejs
- nodemodule
comments: false
---
# github-topics
node module for getting list of topics of a repository on github

[NPM](https://www.npmjs.com/package/github-topics)

## Install

```
npm install github-topics
```

## Usage


```javascript
var github_topics = require('github-topics');
var topics = github_topics.gettopics('https://github.com/Aniket965/blog');
console.log(topics);
// output
// [ 'blog', 'jekyll', 'website', 'projects' ]

```
