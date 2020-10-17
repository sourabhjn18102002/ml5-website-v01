## Contributing --

The website source is in the `source` branch. The site is served from `master`.

Almost all the content for the website can be found in markdown under the `docs/` folder at the root level of the repository.

The naming convention we are using is the following:

* Examples are named: `examples-[name of example].md`
* API Reference files are named: `api-[Class].md`
* Glossary: `glossary-[type].md`

When you add a new page, remember to add the page id to the respective category in the website/sidebars.json file.

If you wish to help develop the website, first you'll need to install the necessary dependencies for Docusaurus.

Clone this repo and start
```
git clone https://github.com/ml5js/ml5-website
cd ml5js.github.io.git
cd website/
npm install
```

And then start the development server from inside the `website/` directory:

```
npm run start
```

This will start a server that reloads when changes are made to the website source code.
save you work first.

To build the website run this script from the `website/` directory:

```bash
npm run build
```
