# Dodge optics lab web site

Our group web site uses the [Hugo Blox](https://hugoblox.com) static site generator with the [Research Group Theme](https://hugoblox.com/templates/details/research-group/). See below for more information.

The [Hugo Blox documentation](https://docs.hugoblox.com) describes how to configure the static site generator and build the website. See [this link](https://docs.hugoblox.com/getting-started/install-hugo/) for instructions on how to edit the website locally. To view the site locally, you will need to change the `baseURL` by commenting out the `baseURL: 'https://www.sfu.ca/lux/'` line and uncommenting the `baseURL: 'http://localhost:1313/'` line in the file `/config/_default/config.yaml`, as shown below.

```
title: 'Dodge Optics Lab' # Website name
baseURL: 'https://www.sfu.ca/lux/' # Website URL
# baseURL: 'http://localhost:1313/' # Local testing
```
