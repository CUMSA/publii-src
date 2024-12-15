# publii-src

## Getting started

Download Publii from [https://getpublii.com/](https://getpublii.com/).

Clone this repository into `~/Documents/Publii/sites/` (for MacOS), or the equivalent for your operating system.

Initialize the submodules, which contain the theme from [CUMSA/publii-theme](https://github.com/CUMSA/publii-theme)

```bash
git submodule update --init --recursive
```

Open Publii and install the following Plugins:

- [External Links](https://marketplace.getpublii.com/plugins/external-links/)

## Publishing

You should publish to [CUMSA/cumsa.org](https://github.com/CUMSA/cumsa.org) to update the website.

Go to "Server" and set the following settings:

- Website URL: `https://cumsa.org`
- Repository URL: `https://github.com/CUMSA/cumsa.org`
- Branch: main
- Username: CUMSA
- Password: A GitHub Personal Access Token with access to the repository
- Commit author: `admin`
- Commit author email: `<database@cumsa.org>`
- Commit message: `Publii: update content`

Then click "Publish" to publish the website.

## Customization

To change the theme, change the [CUMSA/publii-theme](https://github.com/CUMSA/publii-theme) repository and update the submodule.
