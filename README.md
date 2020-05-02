# Installation

* [Install the addon](https://addons.mozilla.org/en-US/firefox/addon/cite-this)
* Open the CiteThis! Sidebar from View > Sidebar > CiteThis!

# Developing

This project uses [Yarn](https://yarnpkg.com/).

Install on macOS using [Homebrew](https://brew.sh/).

```
brew install yarn
```

Create a new Firefox profile for development by opening Firefox and
navigating to `about:profiles`. Create a new profile called
`extension-developer`.

Then, start [webpack](https://webpack.js.org/) in watch mode, and open a
Firefox browser using the profile we created above, which will also watch
changes, using:

```
yarn run develop:watch
```

It is useful to run tests while you are doing development (TDD-style).
To do this, use:

```
yarn run test:watch
```

# Testing

You can run tests a single time using:

```
yarn run test
```

or watch file changes using:
```
yarn run test:watch
```


# Support

Open an issue at:

https://github.com/jamiely/citethis

# Site

https://github.com/jamiely/citethis

# Date Formatters

Uses DateJS format specified http://code.google.com/p/datejs/wiki/FormatSpecifiers

