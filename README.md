# github-topics

[![Greenkeeper badge](https://badges.greenkeeper.io/Rfrazier34/github-topics.svg)](https://greenkeeper.io/)

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
