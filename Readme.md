## GraphQL Tools  - [graphqltools.info](https://graphqltools.info)

## To contribute

1. [Install Jekyll](http://jekyllrb.com) (use the command ```sudo gem install jekyll```)
2. Fork the [GraphQL Info Repo](https://github.com/xaddax/graphql-info/fork)
3. Clone the repo you just forked.
4. Check out the sample posts in `_posts` to see examples for assigning categories and tags, and other YAML data.
5. Add or update a post.
6. **Remember to compile your assets files with Gulp.**
7. Put in Pull Request

## Creating posts

You can use the `initpost.sh` to create your new posts. Just follow the command:

```
./initpost.sh -c Post Title
```

The new file will be created at `_posts` with this format `date-title.md`.

## Front-matter 

When you create a new post, you need to fill the post information in the front-matter, follow this example:

```
---
layout: post
title: "Falando sobre RSCSS"
date: 2016-02-07 18:48:16
image: '/assets/img/rscss/rscss.png'
description: 'Escrevendo CSS sem perder a sanidade. Aprenda uma metodologia que pode salvar muitas dores de cabeça.'
main-class: 'css'
color: '#2DA0C3'
tags:
- css
- metodologia
- frontend
categories:
twitter_text: 'Escrevendo CSS sem perder a sanidade.'
introduction: 'Escrevendo CSS sem perder a sanidade. Com essa introdução, Rico St. Cruz o criador chama a atenção de todos sobre uma metodologia melhor para se escrever CSS.'
---
```

## Running the blog in local

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Install [NodeJS](https://nodejs.org/) (remember to use the latest version)
- Run `npm install`
- Run `npm install -g gulp gulp-cli`
- Run `gulp`


## License

The theme used is free and open source software, distributed under the The MIT License. Visit [Cards Jekyll Template](https://github.com/willianjusten/cards-jekyll-template/) on GitHub to fork and use the original template by [@willian_justen](https://twitter.com/willian_justen).
