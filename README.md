# rajpoudyal/rajpoudyal.github.io

## Usage

Please make sure you have install the [build tools](https://hbs.razonyang.com/en/docs/getting-started/#build-tools) prior to using this template.

## Server

**1. Install dependencies**

```shell
$ npm i
```

Generally, this step only needs to be performed once for each local project.

**2. Start server**

```shell
$ hugo server
```

## Upgrade theme

```shell
$ hugo mod get -u
$ hugo mod npm pack
$ npm i
$ git add go.mod go.sum
$ git commit -m 'Update the theme'
```

## Deployment

Please make sure you've change the `baseURL` on `/config/production/config.toml` before deploying your site.

This template supports Netlify out-of-box. You could find more deployment methods on [Hosting & Deployment](https://gohugo.io/hosting-and-deployment/).

## References

- [English](https://hbs.razonyang.com/en)
