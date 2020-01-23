# Imersys docs-site

This site is built using [hexo](http://hexo.io/). Site content is written in
[Markdown](http://daringfireball.net/projects/markdown/syntax) (and located in
the [`src/`](src/) directory). Pull requests are welcome!

## Local Development

Clone [this repository](https://github.com/imersys/docs-site):

    git clone git@github.com:imersys/docs-site.git && cd docs-site

To install the dependencies and start the local development server:

    npm install && npm run installdocs && npm start

Then load __[`http://localhost:4000/`](http://localhost:4000/)__!

You may need to occasionally need to restart the server if you cause breaking
changes. Just proceed as usual. When developing on the site scripts,
generators, and helpers in `scripts/`, you will need to restart the server on
every change.

## Deployment

    npm run generate

    firebase deploy

## Credits

Source adopted from [A-Frame](https://aframe.io/)  and [Vue's site](https://github.com/vuejs/vuejs.org/).

## License

Licensed under [The MIT License](LICENSE).
