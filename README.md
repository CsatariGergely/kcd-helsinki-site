# Cloud Native Finland Website

This directory contains a [Hugo](https://gohugo.io) web site published via [Netlify](https://www.netlify.com/) to
<https://tag-env-sustainability.cncf.io/>.

When the `main` branch of this repo is updated a fresh build and deploy of the website is executed. Recent Netlify
builds and deployments are listed at <https://app.netlify.com/sites/tag-env-sustainability>.

Add content by adding Markdown files to directories in [./content](./content).

Update layouts for each content type in [./layouts](./layouts/).

Configuration is set in [config.toml](./config.toml).

## Setting up a local dev instance

To set up a local dev environment make sure you have [npm](https://www.npmjs.com/) installed, then run the following:

```sh
git clone git@github.com:cloud-native-finland/cloud-native-finland-site.git
cd cloud-native-finland-site
npm install
```

Then run the site using `npm run serve`. To have the site run locally with a functioning local search, run
`npm run serve:with-pagefind`.

## License

Licensed under the [Creative Commons Attribution 4.0 International license](LICENSE)