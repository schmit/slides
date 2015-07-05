Fork of [reveal.js](https://github.com/hakimel/reveal.js) to make it easy to

- Use Markdown
- Use MathJax
- Deploy on Heroku

## Setup

- Clone repository
- Run `$ npm install`
- Run locally `$ grunt serve`
- Create slides in `content.md`

(requires node.js, npm, grunt)

To deploy to Heroku:
```
heroku create
git push heroku master
```

Based on [Creating Slick HTML Presentations Using reveal.js](http://www.sitepoint.com/creating-slick-html-presentations-using-reveal-js/)

### Notes

To be able to run `grunt`, you might have to install the grunt-cli:
```
npm install -g grunt-cli
```
See the link above, and its link, for pointers.
