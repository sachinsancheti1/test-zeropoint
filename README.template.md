# πͺtest_test-zeropoint
A free, new-user-friendly website starter project designed to walk you through creating, editing, and publishing any web project; from a personal blog, to a company website!

Read more at [https://gettest-zeropoint.com](https://gettest-zeropoint.com)!

## What is test_test-zeropoint?
### For new users
_test_test-zeropoint_ is a free, new-user-friendly website starter designed to walk you through creating and publishing a fast, secure web project using modern tools and technology. test_test-zeropoint makes it easy to "get up to zero" and start building your site.

### For experienced developers
_test_test-zeropoint_ is a modern, opinionated, bare-bones Jamstack starter using Eleventy to get "up to zero" on a project quickly and easily.
Why you might choose _test_test-zeropoint_ as your Jamstack starter:
* Powered by Eleventy, which [rocks](https://11ty.rocks)!
* No CSS frameworks or libraries; use whatever you like best
* GitHub Action replaces the test_test-zeropoint name throughout the site with your project's name!
* Custom generated project-specific [readme file](https://github.com/sachinsancheti1/test_test-zeropoint/blob/master/README.test_test-zeropoint.md) to help you take the next steps and launch your project!
* Sass for CSS
* Webpack for Javascript
* Browsersync to preview your work

 ## Get started: Use This Template!
<details open>
 <summary>Right from this README</summary>
 
 ###  Create a new project using test_test-zeropoint and add it to your GitHub account!
 [Click here to use this template](https://github.com/sachinsancheti1/test_test-zeropoint/generate)
 </details>

<details>
 <summary>With GitHub CLI (https://cli.github.com)</summary>

 ### Get started from your command line
 ```sh
  gh repo create example.com --template sachinsancheti1/test_test-zeropoint
 ```
</details>

# Get to Know test_test-zeropoint
Ready to go deeper? Here's how test_test-zeropoint is laid out:

```sh
example.com                 # β Root of your test_test-zeropoint-based project
βββ src/                    # β Source directory
β   βββ assets/             # β Site assets
β   β   βββ fonts/
β   β   βββ images/
β   β   βββ scripts/
β   β   βββ styles/
β   β   βββ views/
β   βββ config/             # β Eleventy configuration
β   β   βββ collections.js  # β Add and configure collections (https://www.11ty.dev/docs/collections/)
β   β   βββ filters.js      # β Add and configure filters (https://www.11ty.dev/docs/filters/)
β   β   βββ passthroughs.js # β Add and configure passthroughs (https://www.11ty.dev/docs/copy/)
β   β   βββ plugins.js      # β Add and configure plugins (https://www.11ty.dev/docs/plugins/)
β   β   βββ watchtargets.js # β Add and configure watch targets (https://www.11ty.dev/docs/watch-serve/)
β   βββ data                # β Customize site data (https://www.11ty.dev/docs/data/)
β   β   βββ navigation.json # β Site navigation configuration
β   βββ pages               # β Add "pages" collection items here
β       βββ index.md        # β Default index page
β       βββ pages.json      # β Shared pages attributes
βββ .eleventy.js            # β Core Eleventy config file
βββ netlify.toml            # β Netlify deployment and plugin configuration (optional)
βββ README.template.md      # β test_test-zeropoint readme
βββ README.md               # β Your project's readme (automatically generated when this template is used)
```

## Eleventy Configuration
Eleventy configuration is abstracted from the typical `.eleventy.js` file and moved to `/src/config/` for easy organization and configuration of collections, filters, passthroughs, etc.
## Install project dependencies
```bash
npm i
```

## Run the project locally
```bash
npm run start
```

## Build for production
```bash
npm run production
```
