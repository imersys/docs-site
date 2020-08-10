# Imersys docs-site

[Imersys docs site](https://docs.imersys.com/) is built using [hexo](http://hexo.io/). Most of site's actual content is written in [Markdown](http://daringfireball.net/projects/markdown/syntax). Pull requests are always welcome!

## Local Development

Clone [this repository](https://github.com/imersys/docs-site):

    git clone git@github.com:imersys/docs-site.git && cd docs-site

To install the dependencies and start the local development server:

    npm install && npm start

Then load __[`http://localhost:4000/`](http://localhost:4000/)__!

You may need to occasionally need to restart the server if you cause breaking
changes. Just proceed as usual. When developing on the site scripts,
generators, and helpers in `scripts/`, you will need to restart the server on
every change.

## Deployment

GitHub Actions does all the job on generating the bundle (`npm run generate`) and deploying it to GitHub Pages. You simply need to run the following therefore:

    npm version patch

    git push && git push origin --tags

## Credits

Source adopted from [A-Frame](https://aframe.io/)  and [Vue's site](https://github.com/vuejs/vuejs.org/).

## License

Licensed under [The MIT License](LICENSE).
