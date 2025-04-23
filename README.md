
# Flowbotic Documentation

This repository contains the documentation for the Flowbotic platform, built using Mintlify.

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command:

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where docs.json is):

```
mintlify dev
```

### Publishing Changes

Install the Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`
