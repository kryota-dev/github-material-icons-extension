<h1 align="center">Material Icons for GitHub</h1>

<div align="center">

![Dark GitHub example](/assets/example-dark.png)
![Light GitHub example](/assets/example-light.png)

<!-- <p align="center">
  <a href="https://chrome.google.com/webstore/detail/material-icons-for-github/bggfcpfjbdkhfhfmkjpbhnkhnpjjeomc"><img src="https://github.com/Claudiohbsantos/github-material-icons-extension/raw/master/assets/chrome-web-store.png"></a>
  <a href="https://addons.mozilla.org/en-US/firefox/addon/material-icons-for-github/"><img src="https://github.com/Claudiohbsantos/github-material-icons-extension/raw/master/assets/firefox-addons.png"></a>
</p>

<b>Install directly from the <a href="https://chrome.google.com/webstore/detail/material-icons-for-github/bggfcpfjbdkhfhfmkjpbhnkhnpjjeomc">Chrome Web Store</a> | <a href="https://microsoftedge.microsoft.com/addons/detail/material-icons-for-github/khckkdgomkcjjnpgjmdmbceiddlmiolb">Microsoft Edge Addons Store</a> | <a href="https://addons.mozilla.org/en-US/firefox/addon/material-icons-for-github/">Firefox Addons</a></b> -->

</div>

---

<!-- <a href="https://github.com/PKief/vscode-material-icon-theme"><img src="https://img.shields.io/badge/last_built_with_vscode_theme-v5.3.0-blue" /></a>

<img valign="middle" src="https://img.shields.io/chrome-web-store/v/bggfcpfjbdkhfhfmkjpbhnkhnpjjeomc?label=Version%20Available%20in%20Chrome%20Store"> -->

### About

Mirror of the [Material Icons for GitHub](https://chrome.google.com/webstore/detail/material-icons-for-github/ffclplgdbkpbhjgjdnfphdphhjgjgjhn) extension for Chrome and Firefox.

Material Icons for GitHub is a browser Extension that enhances repositories file browsers when navigating github.com. Replace default file/folder icons with material design icons tailored to each file type, tool and purpose in the project.

Based and dependent on the popular [Material Icon Theme](https://github.com/PKief/vscode-material-icon-theme) extension for Visual Studio Code. All icons and file assignments on this project are pulled directly from that project, so any praise or design issues should be raised on the original repository.

### Build locally

```shell
pnpm build
```

### Development

Build only files from `src` folder, without re-downloading dependencies from [Material Icon Theme](https://github.com/PKief/vscode-material-icon-theme)

```shell
pnpm build-src
```

Rebuild extension logos from `src/logo.svg`. Only needed when `src/logo.svg` is changed.

```shell
pnpm rebuild-logos
```

Zip `dist` folder for upload to Chrome Web Store and Firefox. _This script needs Zip to be available on PATH_

```shell
pnpm bundle
```

Update language-map.json with latest language contributions.

```shell
pnpm build-languages
```

---

_Special thanks to [@shivapoudel](https://github.com/shivapoudel) for creating and maintaining the Microsoft Edge version of the extension_

_Original extension developed with [Richard Lam](https://github.com/rlam108)_
