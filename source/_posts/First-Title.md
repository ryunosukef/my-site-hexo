---
title: First Title
date: 2016-03-21 11:50:26
tags:
---
# my first hexo title markdown

## hexo commands

- hexo init my-site-hexo
- cd my-site-hexo
- npm i hexo-deployer-git --save
- vim _config.xml
- hexo delpoy

## change theme refs.[very-simple](https://github.com/lotabout/very-simple)

```
git clone https://github.com/lotabout/very-simple themes/very-simple
npm install hexo-renderer-sass --save
npm install hexo-renderer-jade --save
```

- vim _config.xml

```_config.yml
theme: very-simple
```

- hexo deploy -g
