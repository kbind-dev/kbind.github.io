# kbind.dev

This repository contains the [Hugo](https://gohugo.io) files for [kbind.dev](https://kbind.dev), the official website of the kbind project (formerly known as kube-bind).

## Development

To set up a local development environment, make sure to have `git`, `npm` and `hugo` available. After checking out the repository, make sure dependencies and submodules are pulled:

```sh
$ npm ci && git submodule update --init
```

Afterwards, run `hugo` and visit [localhost:1313](http://localhost:1313):

```sh
$ hugo serve
```
