# NEXT-TYPESCRIPT STARTER

### What's Included

- Styling options
- Page analytics
- SEO setup

#### Styling

Styling options include:

- Vanilla CSS
- Sass/Scss
- Tailwindcss

You can also use modular styling with css or scss.

#### Page Analytics

We added functionalities for both google and fathom analytics in this project, so you can choose one that's suitable for your project.
NB: Create a a `.env.local` file in your root and add your google or fathom analytics id as an environmental variable. Use `NEXT_PUBLIC_GOOGLE_ANALYTICS_ID` for google analytics id and `NEXT_PUBLIC_FATHOM_ANALYTICS_ID` as env variable for fathom analytics.

#### SEO

We setup default seo using the [next-seo package] (https://github.com/garmeeh/next-seo). You can add your site name, site title and site url as environmental variables under the `next.config.js` file. See [the documentation] (https://github.com/garmeeh/next-seo) on how to add seo bits on a per page basis.

#### Other env variables

We advice you create a `.env.local` file in your root folder and add your sensitive environmental variables to this file. For less sensitive environmental variables (like site url and title), add them under the `next.config.js` file.
