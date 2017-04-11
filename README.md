[![Build Status](https://travis-ci.org/MacKentoch/react-director-admin-template.svg?branch=master)](https://travis-ci.org/MacKentoch/react-director-admin-template)

ReactJS version of Director Responsive Admin Template Free
==========

Credits to [web-apps.ninja](http://web-apps.ninja/director-free-responsive-admin-template/) for giving us the original template for free :clap:.

## Preview
![preview](https://raw.githubusercontent.com/MacKentoch/react-director-admin-template/master/preview/preview.png)

[Launch preview here](https://mackentoch.github.io/react-director-admin-template)

## Content

- Director template (see [original one here]((http://web-apps.ninja/director-free-responsive-admin-template/)))
- ReactJS
- Redux (*+ hot reload + redux devtools extension*)
  - since v0.2.0: adopted redux ducks (*for clarity*)
- *...more content coming soon*

## Usage

### Prerequisite

> Ensure to have NodeJS v6.x MINIMUM.

### Install
```bash
npm install
```

### bundle dev mode

*General case:*
```bash
npm run dev
```

*Windows - particular - case::*
```bash
npm run dev-win
```

### dev : hot reload mode

Development mode = best dev experience (*hot reload, redux devtools extension...*).

*General case:*
```bash
npm run start
```

*Windows - particular - case::*
```bash
npm run start-win
```
> Then go to localhost:3000

### bundle production mode

*General case:*
```bash
npm run prod
```
*Windows - particular - case::*
```bash
npm run prod-win
```

### run production

In `Development` ReactJS is `not optimized at all` (*you may even find the application to be slow*).

*ReactJS shows its real power and is `amazing fast` when bundled in `production`.*

*General case:*
```bash
npm run prod-server
```
> Then go to localhost:8081
