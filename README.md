# Morten Kristiansen's Electronic Business Card

This is a simple and minimalist website built with Jekyll designed for developers that want to show of their portfolio.

THe Theme is heavily inspured by the [Particle Theme](https://github.com/nrandecker/particle/fork). It features:

- Gulp
- SASS
- Sweet Scroll
- Particle.js
- BrowserSync
- Font Awesome and Devicon icons
- Google Analytics
- Info Customization

## Basic Setup

1. Install [Jekyll](http://jekyllrb.com)
2. Fork the [repo](https://github.ibm.com/morten/bizCard/fork)
3. Clone the repo you just forked.
4. Edit `_config.yml` to personalize your site.

## Site and User Settings

You have to fill some informations on `_config.yml` to customize your site.

```yaml
# Site settings
description: A blog about lorem ipsum dolor sit amet
baseurl: "" # the subpath of your site, e.g. /blog/
url: "http://localhost:3000" # the base hostname & protocol for your site

# User settings
username: Lorem Ipsum
user_description: Anon Developer at Lorem Ipsum Dolor
user_title: Anon Developer
email: anon@anon.com
twitter_username: lorem_ipsum
github_username:  lorem_ipsum
gplus_username:  lorem_ipsum
```

**Don't forget to change your url before you deploy your site!**

## Color and Particle Customization

- Color Customization
  - Edit the sass variables
- Particle Customization
  - Edit the json data in particle function in app.js
  - Refer to [Particle.js](https://github.com/VincentGarreau/particles.js/) for help

## Running the blog in local

In order to compile the assets and run Jekyll on local you need to follow those steps:

- Install [NodeJS](https://nodejs.org/)
- Run `npm install`
- Run `gulp`

## Deploy the Site

A Travis file (.travis.yml) and a `cibuild` script is provided to automatically deploy to github (gh-pages branch) on each push to `master`.

Make sure to customize repo path and to set the GH_TOKEN value prior to enabling the repo in the Travis console.

## Questions

Having any issues file a [GitHub Issue](https://github.com/nrandecker/particle/issues/new).

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

## Credits

This theme is a blatant rip-off of the work by [Nathan Rendecker](https://github.com/nrandecker/particle/fork) :)
