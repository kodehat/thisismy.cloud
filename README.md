# This Is My Cloud Website ![](https://img.shields.io/badge/license-MIT-blue.svg) [![Netlify Status](https://api.netlify.com/api/v1/badges/b7a68c6a-e6e8-4f0d-a889-0153d6df1e52/deploy-status)](https://app.netlify.com/sites/pensive-villani-85f917/deploys)

> <thisismy.cloud> static website built with Hugo.

This repo contains <thisismy.cloud> website and is built with [Hugo](https://gohugo.io/).

## Development

Linux, OS X & Windows:

`hugo` has to be installed.

```sh
hugo serve -D
```

## Deployment

Linux, OS X & Windows:

`hugo` has to be installed.

```sh
hugo --gc --minify --enableGitInfo
```

You'll find all required files in the `public` folder.

### Additions For Netlify

Set the following environment variables:

| Key                | Value      |
| :----------------- | :--------- |
| HUGO_ENABLEGITINFO | true       |
| HUGO_ENV           | production |
| HUGO_VERSION       | 0.92.0     |

## Usage example

This website acts as a demo, so just head over to <https://www.thisismy.cloud> to see this repo in action.

## Meta

CodeHat – [@CodeHat](https://twitter.com/CodeHat)

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/kodehat](https://github.com/kodehat)

## Contributing

1. Fork it (<https://github.com/kodehat/thisismy.cloud/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
