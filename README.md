[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/gomah/bluise)

# Contact Tracing - Collaborate, Inform, Protect.

Contact Tracing is a privacy-first system for anonymous Bluetooth proximity-based exposure alerting based on voluntary symptom sharing. Communities of close contacts can begin protecting themselves with Contact Tracing immediately; we don't need millions of people to install the app, and we don't have to wait for testing to ramp up. By installing Contact Tracing and reporting symptoms, you and the people you interact with can create your own early warning system to detect and respond to any infectious disease such as COVID-19.
[Download APK](https://www.dropbox.com/s/21mpc5j5hs97y4p/app-release.apk?dl=1)

So far we've got:

- Blog w/ posts, including pagination.
- Configurable manifest & global settings.
- CSS Markdown (Thanks to [https://github.com/iandinwoodie/github-markdown-tailwindcss/blob/master/markdown.css](iandinwoodie)).
- Dynamic pages.
- PWA ready.
- SEO ready for posts & pages.
- Signup form (using Netlify Forms).
- Tools (Commitlint, Husky).
- Typescript.

Few things I'd like to add in the future:

- Contact form under \_slug.
- Dynamic sections/widgets.
- Responsive CSS markdown.
- Tests

## Quickstart

### Prerequisites

- [Yarn](https://yarnpkg.com/lang/en/docs/install/#mac-tab)
- [Node.js](https://nodejs.org/en/)

```bash
# ensure you have the prerequisites
# install
brew install node && brew install yarn

# OR update
brew update && brew upgrade && brew install yarn

# install dependencies
yarn install

# serve with hot reload at localhost:3000
yarn dev

# build for production with minification
yarn generate

# run all tests
yarn test
```

### Using Netlify CMS

1. Deploy to Netlify.
2. Enable Identity under Settings.
3. Configure registration preferences & external providers if needed.
4. Enable Git Gateway.

_Note: You'll need to specify the Netlify URL when browsing the admin page locally._
