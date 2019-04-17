# MOMENTS

A [GatsbyJS](https://www.gatsbyjs.org/) personal blog starter. <br /><br />

[![GitHub license][mit-badge]][mit]
[![GitHub tag][tag-badge]][tag]
[![GitHub stars][stars-badge]][stars]
![contributors][contributors-badge]
[![PRs Welcome][prs-badge]][prs]
[![Code of Conduct][coc-badge]][coc]
[![code style prettier][prettier-badge]][prettier]
[![Tweet][twitter-badge]][twitter]

  <br />

![](static/screens/gatsby-starter-personal-blog.gif) <br />

  <br />

See Example Site » [demo website](https://confident-gates-1fd25c.netlify.com//) <br />For more information visit » [MOMENTS](https://dev.greglobinski.com/gatsby-starter-personal-blog/)

## Description

Member engagement is more art than engineering. But once we understand the art of engagement, it is important to employ the engineering with beautiful, compelling dialogue bundles

## Features:

- Customizable
- Easy editable content in Markdown files (posts, pages and parts)
- Easily restyled through theme object
- Styling with JSS
- Post categories
- Post list filtering
- Full text searching (Algolia)
- Contact form (Netlify form handling)
- Material UI (@next)
- RSS feed
- Full screen mode
- User adjustable articles’ body copy font size
- Social sharing (Twitter, Facebook, Google, LinkedIn)
- PWA (manifest.json, offline support, favicons)
- Google Analytics
- Favicons generator (node script)
- Components lazy loading with AsyncComponent (social sharing, info box)
- ESLint (google config)
- Prettier code styling
- Custom webpack CommonsChunkPlugin settings
- Webpack BundleAnalyzerPlugin

## Prerequisites

If you do not have Gatsby Cli installed yet, do it first.

```text
npm install --global gatsby-cli
```

More information on [GatsbyJS.org](https://www.gatsbyjs.org/tutorial/part-one)

## Getting started

Install the starter using Gatsby Cli `gatsby new` command.

```text
gatsby new [NEW_SITE_DIRECTORY_FOR_YOUR_BLOG] https://github.com/greglobinski/gatsby-starter-personal-blog.git
```

Go into the newly created directory and run

```text
gatsby develop
```

to hot-serve your website on http://localhost:8000 or

```text
gatsby build
```

to create static site ready to host (/public).

##### External services

The starter uses external services for some functions: comments, searching, analytics. To use them you have to secure some access data. All services are free to use or have generous free tiers big enough for a personal blog.

Create an `.env` file like below in the root folder. Change `...` placeholders with real data.

```text
GOOGLE_ANALYTICS_ID=...
ALGOLIA_APP_ID=...
ALGOLIA_SEARCH_ONLY_API_KEY=...
ALGOLIA_ADMIN_API_KEY=...
ALGOLIA_INDEX_NAME=...
FB_APP_ID=...
```

### Instructions & tutorials

- [How to install, setup and add new content to a Blog starter](https://dev.greglobinski.com/install-blog-starter/)
- [How to customize the PersonalBlog starter's appearance](https://dev.greglobinski.com/customize-personal-blog-starter/)
- [Setup Algolia account for your GatsbyJS blog](https://dev.greglobinski.com/setup-algolia-account/)
- More articles soon at [Front-end web development with Greg](https://dev.greglobinski.com/)

## Windows users

You should take a look at this: [Gatsby on Windows](https://www.gatsbyjs.org/docs/gatsby-on-windows/)

## Software Engineers

-  Strategic Machines [@greglobinski](https://github.com/greglobinski)

See also the list of [contributors](https://github.com/greglobinski/gatsby-starter-personal-blog/graphs/contributors) who participated in this project.

## Contributing

- Fork the repo
- Create your feature branch (git checkout -b feature/fooBar)
- Commit your changes (git commit -am 'Add some fooBar')
- Push to the branch (git push origin feature/fooBar)
- Create a new Pull Request

## Licence

MIT License

Copyright (c) 2017 gatsbyjs <br />Copyright (c) 2019 Strategic Machines

[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square
[coc]: https://github.com/greglobinski/gatsby-starter-personal-blog/blob/master/CODE_OF_CONDUCT.md
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
[twitter]: https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fgreglobinski%2Fgatsby-starter-personal-blog
[twitter-badge]: https://img.shields.io/twitter/url/https/github.com/greglobinski/gatsby-starter-personal-blog.svg?style=social
[tag-badge]: https://img.shields.io/github/tag/greglobinski/gatsby-starter-personal-blog.svg
[tag]: https://github.com/greglobinski/gatsby-starter-personal-blog
[stars-badge]: https://img.shields.io/github/stars/greglobinski/gatsby-starter-personal-blog.svg
[stars]: https://github.com/greglobinski/gatsby-starter-personal-blog/stargazers
[contributors-badge]: https://img.shields.io/github/contributors/greglobinski/gatsby-starter-personal-blog.svg
[prettier-badge]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square
[prettier]: https://github.com/prettier/prettier
[mit-badge]: https://img.shields.io/github/license/greglobinski/gatsby-starter-personal-blog.svg
[mit]: https://github.com/greglobinski/gatsby-starter-personal-blog/blob/master/LICENSE
