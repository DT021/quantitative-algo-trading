# Quantitative Algorithmic Trading
The proposed system helps the people in the stock market business and make it easy for them to decide where to invest their valuable money and what is the best time to sell the stocks they own. The data will be provided by the Alpha Vantage API which provides current data of any NASDAQ listed company with their stock values and past performances. It also provides years worth of data whenever needed. The system is intended to be distributed under the MIT License.


## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [What's included](#whats-included)
* [System Architecture Overview](#system-architecture-overview)
* [Contributing](#contributing)
* [Documentation](#documentation)

## Installation

``` bash
# Go to the directory where you want to clone the repo
$ cd dir_name

# Clone the repo
$ git clone https://github.com/bjpadhy/quantitative-algo-trading.git quantitative-algo-trading

# Go into app's directory
$ cd quantitative-algo-trading

# Install app's dependencies
$ npm install
```

## Usage

``` bash
# Serve with hot reload at localhost:3000. Port number maybe different. Check terminal logs.
# Use this for development
$ npm run serve

# Build for production with minification.
$ npm run build
```

## What's included
Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:
``` 
quantitative-algo-trading
├── build/
├── pug/
│   ├── _layout/
│   ├── _partial/
│   ├── base/
│   ├── buttons/
│   ├── icons/
│   ├── notifications/
│   ├── ...
│   ├── index.pug
│   └── ...
├── dist/
│   ├── assets/
│   │   ├── brand/
│   │   ├── favicon/
│   │   ├── icons/
│   │   ├── img/
│   ├── base/
│   ├── buttons/
│   ├── css/
│   ├── icons/
│   ├── js/
│   ├── notifications/
│   ├── scss/
│   ├── vendors/
│   ├── ...
│   ├── index.html
│   └── ...
├── src/
│   ├── assets/
│   │   ├── brand/
│   │   ├── favicon/
│   │   ├── icons/
│   │   ├── img/
│   ├── base/
│   ├── buttons/
│   ├── css/
│   ├── icons/
│   ├── js/
│   ├── notifications/
│   ├── scss/
│   ├── vendors/
│   ├── ...
│   ├── index.html
│   └── ...
├── nodemon.json
├── package-lock.json
└── package.json
```

## System Architecture Overview

![System Architecture Overview](https://lh3.googleusercontent.com/UyvbMnq5CGPhDkpGEi84e6lARxxLycEBW0QQc1_heO4C_DT45dWa653UL4e5cZHbpOK4PQ_ehY59TJCY8ji8S3qYZ-57Iuc_WL4djkT6ax20haJkeqKLnbM-9wkJda_XkTppHHzvJ5azz_UcFUHGCubn5foTU5OzA7d0n27Ne2J9k2NlPfvld2hp-f5g0lkvAXnIgiP-oxd-1MF5nzjHRIJlS086Q_Pgyp_JyZY0sOiG6BtRhQRWhWvfN5Ni7WAUByVSCToYqsLfGVsA6Dd5dfjvHD06C_nPi2Wg9QCKitXUjlWy3QHrn9Ax5V6MwchCOwEh_ys9D_Q28Rbm1YR7GcejZCHYfzC6_kQIZGcbedzm4GTr1ekJaDxU5c3Vj_yDjEBvQQEMBIjNPzkfe467h4j4dG7M28HLauGcrti97e9Mm_gHy06F3ThvpEpeecitkxktAmzAIwIJXzxCLP1pqFxm76Kjupt5z08bWmSkCxB4ptQ0171wtapibfLw-1PyUyN6Mxq6VnxfkTAacYCNUmFNmKUVrTTzUUeceP4kb6tOM11RLwcbcVWxamAWaiRmyCrCvwPPpIbwNIZx2VZRjMvkgtDdLFAbD2aElHHOaM1hMzl-Vv49Hg7Q8KwuPgjT3iWS0BVBybLk72d99FgXruOKVyqyWxJLe_9WECjqFFYQtyqmWcVsqC7sG1OrO1zZt4uz0qRQazhB0t2y5ODGeDVu83Y611EC_T9yiktcnKEyBnTa8nTkYGA=w2320-h1642-no)

## Contributing

Edit files only in the dist/ directory. When you run ```npm run serve``` the project will be served on localhost from dist/ with hot reload. i.e any changes made and saved to a file will be visible in browser without having to reload the page. When all changes are stable and nothing seems to be broken, copy entire contents of dist/ into src/ and run ```npm run build``` to build dist files.

### Committing and Pushing to GitHub

Stage all changes. **Include a descriptive commit message clearly stating the changes made.** Issue a Pull Request to master only if a module is complete, 100% working and doesn't break anything else. **Biswaranjan Padhy** will resolve any conflicts and merge to master as and when required.

- If you have no experience with Git then follow the quick guide at [GitHowTo](https://githowto.com/)

## Documentation

- Documentation for the CoreUI Bootstrap Template is hosted at [CoreUI](https://coreui.io/docs/getting-started/introduction/#coreui-admin-template)
- Design and Business documents pertaining to this project are located at [Documentation](https://drive.google.com/open?id=1f4cEnPXLHRUnu_AwKlCRpet3rGzvd-_P)

**The ReadME shall be updated with future changes and enhancements**
