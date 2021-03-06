# sanity-template-gatsby-portfolio

_Clean React.js starting point for portfolios, project listings or case studies._

[See demo](https://sanity-template-gatsby-portfolio-web.netlify.com/).

This template repo is used by Sanity.io to easily create deployed and configured projects through a web interface. You can test it out by [creating this project](https://www.sanity.io/create/?template=sanity-io%2Fsanity-template-gatsby-portfolio).

The template contains both the Sanity Studio and a front-end in Gatsby. Both are deployed on Netlify.

Want to make a template for Sanity and your favourite front-end framework? We’re still maturing [sanity.io/create](https://sanity.io/create) and our APIs, but do tell us about it on [slack.sanity.io](https://slack.sanity.io).

![The Gatsby and Sanity powered portfolio frontend](https://github.com/sanity-io/sanity-template-gatsby-portfolio/blob/main/assets/frontend.jpg?raw=true)

## Local development

You develop the templates in `/template`, and review your changes in `/build`.

1. **Install dependencies with `npm install` in the root folder.** This will install the template development tool that watches changes in the `/template` folder and output the template to `/build`.

2. **Run `npm run dev` in root folder.** This will build the template files to `/build`. This is how the code will look for those who install the project later.

3. **Run `npm install` in `./build/web` and `sanity install` in `/build/studio`** This will install the necessary dependencies for the Gatsby front-end and the Studio.

4. **Run `npm run dev` in `./build/web` and `sanity start` in `/build/studio`**. This will start the development servers for the Gatsby front-end and Sanity Studio.

## Notes

When developing, you may change `projectId` and `dataset` in `dev/template-values-development.json` to connect with a different Sanity project.
