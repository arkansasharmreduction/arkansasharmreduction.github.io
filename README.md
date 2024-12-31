## Local Development

This is a simple static HTML site. To add new pages, create a new folder with the path you want to serve that page at (`/resources` for example) and give it an `index.html` file.

This project uses [`sass` ](https://sass-lang.com/guide/) to add in a bit of extra functionality to our CSS. So, if you want to make style changes, you should instsall sass, run `sass --watch css`, and edit the relevant `.scss` file. That command line tool will automatically update a generated `.css` file which is actually used to apply styles.

The easiest way to see changes you make locally is by running a local webserver. There are lots of tools, but a simple one is [http-server](https://www.npmjs.com/package/http-server#globally-via-homebrew).

## Deploying Changes

This site is hosted on [GitHub Pages](https://pages.github.com/). Any changes that are merged into the `master` branch will automatically be deployed and update the site at https://www.arkansasharmreduction.org/


